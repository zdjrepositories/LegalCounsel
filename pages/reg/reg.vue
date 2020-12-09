<template>
	<view class="content">
		<view class="input-group">
			<view class="input-row border">
				<text class="title">账号：</text>
				<m-input type="text" focus clearable v-model="username" placeholder="请输入账号"></m-input>
			</view>
			<view class="input-row border">
				<text class="title">验证码：</text>
				<m-input type="text" v-model="code" placeholder="请输入验证码"></m-input>
				<view class="send-code-btn" @click="sendSmsCode">{{codeDuration ? codeDuration + 's' : '发送验证码' }}</view>
			</view>
			<view class="input-row border">
				<text class="title">邮箱：</text>
				<m-input type="text"  clearable v-model="email" placeholder="请输入邮箱"></m-input>
			</view>
			
			<view class="input-row border">
				<text class="title">密码：</text>
				<m-input type="password" displayable v-model="password" placeholder="请输入密码"></m-input>
			</view>
			<view class="input-row">
				<text class="title">确认密码：</text>
				<m-input type="password" displayable v-model="confirmPassword" placeholder="请确认密码"></m-input>
			</view>
		</view>
		<view class="btn-row">
			<button type="primary" class="primary" @tap="register">注册</button>
		</view>
	</view>
</template>

<script>
	import mInput from '../../components/m-input.vue';

	export default {
		components: {
			mInput
		},
		data() {
			return {
				username: '',
				password: '',
				email: '',
				confirmPassword: ''
			}
		},
		methods: {
			register() {
				/**
				 * 客户端对账号信息进行一些必要的校验。
				 * 实际开发中，根据业务需要进行处理，这里仅做示例。
				 */
				if (this.username.length < 6) {
					uni.showToast({
						icon: 'none',
						title: '账号最短为 6 个字符'
					});
					return;
				}
				if (this.password.length < 6) {
					uni.showToast({
						icon: 'none',
						title: '密码最短为 6 个字符'
					});
					return;
				}
				if (this.password !== this.confirmPassword) {
					uni.showToast({
						icon: 'none',
						title: '两次密码输入不一致'
					});
					return;
				}

				const data = {
					username: this.username,
					password: this.password
				}
				uniCloud.callFunction({
					name: 'user-center',
					data: {
						action: 'register',
						params: data
					},
					success(e) {
						console.log("注册成功", e);

						if (e.result.code === 0) {
							uni.showToast({
								title: '注册成功'
							});
							uni.setStorageSync('uniIdToken', e.result.token)
							uni.setStorageSync('username', e.result.username)
							uni.reLaunch({
								url: '../main/main',
							});
						} else {
							uni.showModal({
								content: JSON.stringify(e.result),
								showCancel: false
							})
						}
					},
					fail(e) {
						uni.showModal({
							content: JSON.stringify(e),
							showCancel: false
						})
					}
				})
			}
		}
	}
</script>

<style>
.send-code-btn {
		width: 120px;
		text-align: center;
		background-color: #0bc99d;
		color: #FFFFFF;
	}
</style>
