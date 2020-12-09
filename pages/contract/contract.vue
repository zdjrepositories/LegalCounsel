<template>
	<view class="page">
		<!-- 带图标 -->
		<uni-collapse>
			<uni-collapse-item title="保证合同" thumb="../../static/img/resizeApi3.png">
			    <navigator url="./baozhenghetong">
				<view style="padding: 30rpx;">
			        两方保证合同
			    </view>
				 </navigator>
			</uni-collapse-item>
			<uni-collapse-item title="租赁合同" thumb="../../static/img/resizeApi3.png">
				 <navigator url="./dianpuzulinhetong">
			    <view style="padding: 30rpx;">
			        店铺租赁合同
			    </view></navigator>
			</uni-collapse-item>
				 
		    <uni-collapse-item title="买卖合同" thumb="../../static/img/resizeApi3.png">
				 <navigator url="./maimaihetong">
		        <view style="padding: 30rpx;">
		            两方买卖合同
		        </view>
				</navigator>
		    </uni-collapse-item>
		    <uni-collapse-item title="供水/电/气/热力合同" thumb="../../static/img/resizeApi3.png">
		        <view style="padding: 30rpx;">
		            待补充
		        </view>
		    </uni-collapse-item>
			<uni-collapse-item title="赠与合同" thumb="../../static/img/resizeApi3.png">
			   <view style="padding: 30rpx;">
			       待补充
			   </view>
			</uni-collapse-item>
			<uni-collapse-item title="借款合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			
			<uni-collapse-item title="租赁合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="保理合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="融资租赁合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="承揽合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="建设工程合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="运输合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="技术合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="保管合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="仓储合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="委托合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="中介合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="行纪合同" thumb="../../static/img/resizeApi3.png">
			    <view style="padding: 30rpx;">
			        待补充
			    </view>
			</uni-collapse-item>
			<uni-collapse-item title="旅游合同" thumb="../../static/img/resizeApi3.png">
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
