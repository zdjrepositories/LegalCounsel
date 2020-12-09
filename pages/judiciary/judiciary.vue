<template>
	<view class="page">
		<!-- 带图标 -->
		<uni-collapse>
		    <uni-collapse-item title="兰州市" thumb="../../static/img/resizeApi11.png">
		        <view style="padding: 30rpx;">
		          安宁区安宁堡街道司法所
		        </view>
		        <view style="padding: 30rpx;">
		          安宁区银滩路街道司法所
		        </view>
				<view style="padding: 30rpx;">
				  安宁区培黎街道司法所
				</view>
				<view style="padding: 30rpx;">
				  城关区白银路街道司法所
				</view>
				<view style="padding: 30rpx;">
		          城关区张掖路街道司法所
		        </view>
		        <view style="padding: 30rpx;">
		          榆中县和平镇司法所
		        </view>
				<view style="padding: 30rpx;">
				  皋兰县忠和镇司法所
				</view>
				
		    </uni-collapse-item>
		    <uni-collapse-item title="张掖市" thumb="../../static/img/resizeApi11.png">
		        <view style="padding: 30rpx;">
		          甘州区安阳乡司法所
		        </view>
		        <view style="padding: 30rpx;">
		          甘州区北街街道司法所
		        </view>
		        <view style="padding: 30rpx;">
		           甘州区长安乡司法所
		        </view>
		        <view style="padding: 30rpx;">
		          临泽县板桥镇司法所
		        </view>
		        <view style="padding: 30rpx;">
		          临泽县平川镇司法所
		        </view>
		        
		    </uni-collapse-item>
			<uni-collapse-item title="白银市" thumb="../../static/img/resizeApi11.png">
			  <view style="padding: 30rpx;">
			    白银区纺织路街道司法所
			  </view>
			  <view style="padding: 30rpx;">
			    白银区工农路街道司法所
			  </view>
			  <view style="padding: 30rpx;">
			     靖远县北滩乡司法所
			  </view>
			  <view style="padding: 30rpx;">
			    靖远县东湾镇司法所
			  </view>
			  <view style="padding: 30rpx;">
			    靖远县刘川镇司法所
			  </view>
			  
			</uni-collapse-item>
			<uni-collapse-item title="定西市" thumb="../../static/img/resizeApi11.png">
			   <view style="padding: 30rpx;">
			       待补充
			   </view>
			</uni-collapse-item>
			<uni-collapse-item title="武威市" thumb="../../static/img/resizeApi11.png">
			   <view style="padding: 30rpx;">
			       待补充
			   </view>
			</uni-collapse-item>
			<uni-collapse-item title="天水市" thumb="../../static/img/resizeApi11.png">
			   <view style="padding: 30rpx;">
			       待补充
			   </view>
			</uni-collapse-item>
			<uni-collapse-item title="临夏回族自治州" thumb="../../static/img/resizeApi11.png">
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
