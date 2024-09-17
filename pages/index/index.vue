<template>
	<view class="index-box">
		<swiper class="banner-swipper" indicator-dots indicator-color="rgba(255,255,255,0.5)" indicator-active-color="#ffffff" autoplay :interval="4000">
			<swiper-item class="swiper-item">
				<image src="../../static/images/01.png"></image>
			</swiper-item>
			<swiper-item class="swiper-item">
				<image src="../../static/images/02.png"></image>
			</swiper-item>
		</swiper>
	</view>
</template>

<script>
	import jingBanner from '@/components/common/jing-banner.vue'
	import categoryBox from './components/category-box.vue'
	export default {
		components: {jingBanner,categoryBox},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
