<template>
	<view>
		<web-view :src="pdfUrl"></web-view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				pdfUrl:'',
				from:''
			}
		},
		onLoad() {
			/**
			 * 浏览情景
			 */
			
			// 浏览情景1:浏览本地的pdf文件
			this.pdfUrl = this.pdfUrl = '/hybrid/html/web/viewer.html?file=./pdf/maimaihetong.pdf'
			
			// 浏览情景2:浏览在线的pdf文件
			// this.pdfUrl = '/hybrid/html/web/viewer.html?file='+encodeURIComponent(pdfUrl)
		
		}
	}
</script>

<style>

</style>

