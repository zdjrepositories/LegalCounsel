<template>
	<view class="page">
		<!-- 带图标 -->
		<uni-collapse>
		    <uni-collapse-item title="全国人大法律库" thumb="../../static/img/resizeApi.png">
		        <view style="padding: 30rpx;">
		          《中华人民共和国宪法》
		        </view>
		        <view style="padding: 30rpx;">
		          《中华人民共和国刑法》
		        </view>
				<view style="padding: 30rpx;">
		          《中华人民共和国国旗法》
		        </view>
				<view style="padding: 30rpx;">
				  《中华人民共和国国徽法》
				</view>
				<view style="padding: 30rpx;">
				  《中华人民共和国专利法》
				</view>
				
		    </uni-collapse-item>
		    <uni-collapse-item title="国务院行政法规库" thumb="../../static/img/resizeApi.png">
		        <view style="padding: 30rpx;">
					《全国经济普查条例》
		        </view>
				<view style="padding: 30rpx;">
					《企业事业单位内部治安保卫条例》
				</view>
				<view style="padding: 30rpx;">
					《人民银行行政许可实施办法颁布》
				</view>
				<view style="padding: 30rpx;">
					《国有企业法律顾问管理办法》
				</view>
				<view style="padding: 30rpx;">
					《粮食流通管理条例》
				</view>
				<view style="padding: 30rpx;">
					《病原微生物实验室生物安全管理条例》
				</view>
		    </uni-collapse-item>
			<uni-collapse-item title="立法/司法解释库" thumb="../../static/img/resizeApi.png">
			   <view style="padding: 30rpx;">
			       待补充
			   </view>
			</uni-collapse-item>
			<uni-collapse-item title="国务院部委规章库" thumb="../../static/img/resizeApi.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="国家规范性文件库" thumb="../../static/img/resizeApi.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="军事法规库" thumb="../../static/img/resizeApi.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="国家行业规范库" thumb="../../static/img/resizeApi.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="甘肃省人大法规库" thumb="../../static/img/resizeApi.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="甘肃省政府规章库" thumb="../../static/img/resizeApi.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="甘肃省规范性文件库" thumb="../../static/img/resizeApi.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
		</uni-collapse>
	</view>
</template>

<script>
import uniCollapse from '../../components/uni-collapse/uni-collapse.vue'
import uniCollapseItem from '../../components/uni-collapse-item/uni-collapse-item.vue'
export default {
    components: {uniCollapse,uniCollapseItem}   
}
</script>
<style>
	
	.page {
		width: 100%;
		background-color: #ebebeb;
	}
	
</style>
