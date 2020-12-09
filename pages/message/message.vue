<template>
    <view>
        <view class="uni-padding-wrap">
            <!-- 评论区 start -->
            <view class="uni-comment">
                <view class="uni-comment-list">
                    <view class="uni-comment-face">
                        <image src="../../static/img/logo.png" mode="widthFix"></image>
                    </view>
                    <view class="uni-comment-body">
                        <view class="uni-comment-top">
                            <text>网友</text>
                        </view>
                       
                        <view class="uni-comment-content">买二手房没有房屋买卖协议，对方不肯交房怎么办？</view>
						<view class="uni-comment-date">
						    <text>2020/07/22 14:55</text>
							<view class="uni-comment-replay-btn">2回复</view>
						</view>
						
                    </view>
                </view>
                <view class="uni-comment-list">
                    <view class="uni-comment-face">
                        <image src="../../static/img/logo.png" mode="widthFix"></image>
                    </view>
                    <view class="uni-comment-body">
                        <view class="uni-comment-top">
                            <text>马克一天</text>
                        </view>
                        <view class="uni-comment-content">公司可以对员工罚款吗？</view>
						<view class="uni-comment-date">
						    <text>2020/07/28 15:43</text>
							<view class="uni-comment-replay-btn">3回复</view>
						</view>
                    </view>
                </view>
                <view class="uni-comment-list">
                    <view class="uni-comment-face">
                        <image src="../../static/img/logo.png" mode="widthFix"></image>
                    </view>
                    <view class="uni-comment-body">
                        <view class="uni-comment-top">
                            <text>今生缘</text>
                        </view>
                        <view class="uni-comment-content">信用卡遗失被冒用，谁担责？</view>
                        <view class="uni-comment-date">
                            <text>2020/08/10 07:55</text>
							<view class="uni-comment-replay-btn">1回复</view>
                        </view>
                    </view>
                </view>
                <view class="uni-comment-list">
                    <view class="uni-comment-face">
                        <image src="../../static/img/logo.png" mode="widthFix"></image>
                    </view>
                    <view class="uni-comment-body">
                        <view class="uni-comment-top">
                            <text>小猫咪</text>
                        </view>
                        <view class="uni-comment-content">公司股东设立公司时法律顾问能做什么？</view>
                        <view class="uni-comment-date">
                            <view>2天前</view>
                            <view class="uni-comment-replay-btn">5回复</view>
                        </view>
                    </view>
                </view>
            </view>
        </view>
    </view>
</template>

<script>
    export default {
        data() {
            return {
                title: "评论界面"
            }
        }
    }
</script>

<style>
    /* comment */
    page {
        background-color: #f8f8f8;
    }

    .uni-padding-wrap {
        padding: 30upx;
    }

    view {
        font-size: 28upx;
    }

    .uni-comment {
        padding: 5rpx 0;
        display: flex;
        flex-grow: 1;
        flex-direction: column;
    }

    .uni-comment-list {
        flex-wrap: nowrap;
        padding: 10rpx 0;
        margin: 10rpx 0;
        width: 100%;
        display: flex;
    }

    .uni-comment-face {
        width: 70upx;
        height: 70upx;
        border-radius: 100%;
        margin-right: 20upx;
        flex-shrink: 0;
        overflow: hidden;
    }

    .uni-comment-face image {
        width: 100%;
        border-radius: 100%;
    }

    .uni-comment-body {
        width: 100%;
    }

    .uni-comment-top {
        line-height: 1.5em;
        justify-content: space-between;
    }

    .uni-comment-top text {
        color: #0A98D5;
        font-size: 24upx;
    }

    .uni-comment-date {
        line-height: 38upx;
        flex-direction: row;
        justify-content: space-between;
        display: flex !important;
        flex-grow: 1;
    }

    .uni-comment-date view {
        color: #666666;
        font-size: 24upx;
        line-height: 38upx;
    }

    .uni-comment-content {
        line-height: 1.6em;
        font-size: 28upx;
        padding: 8rpx 0;
    }

    .uni-comment-replay-btn {
        background: #FFF;
		float: right;
        font-size: 24upx;
        line-height: 28upx;
        padding: 5rpx 20upx;
        border-radius: 30upx;
        color: #333 !important;
        margin: 0 10upx;
    }
</style>
