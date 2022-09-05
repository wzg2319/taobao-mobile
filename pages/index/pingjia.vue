<template>
	<view class="beijing">
		<view class="pjbt">
			<view class="pjbtz">
					
					<image src="../../static/heifanhui.png" mode=""></image>
	
		<p>发表评价</p>
				</view>
		<view class="pjbty">
			<p>发布</p>

			</view>
		
		</view>
		<view class="pjz">
			<view class="pjzs">
				<image src="../../static/logo.png" mode=""></image>
			<p>这里是商品描述</p>
			
			</view>
		<view class="pjms">
			<p>描述相符</p>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
		</view>
	<view class="pjsr">
		<input class="uni-input" confirm-type="search">
		<image src="../../static/pingjia.png" mode=""></image>
		<view class="pjkz">
			<p>公开</p>
			<p>公开信息 大家可以看我</p>
		</view>
	</view>
		</view>
		<view class="pjx">
			<p>xxx旗舰店</p>
			<view class="pjxx">
				<p>物流服务</p>
				<image src="../../static/xingxing.png" mode=""></image>
				<image src="../../static/xingxing.png" mode=""></image>
				<image src="../../static/xingxing.png" mode=""></image>
				<image src="../../static/xingxing.png" mode=""></image>
				<image src="../../static/xingxing.png" mode=""></image>
			</view>
		<view class="pjxxx">
			<p>服务态度</p>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
			<image src="../../static/xingxing.png" mode=""></image>
		</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style lang="scss">
	.pjxxx{display: flex;}
	.pjxx{display: flex;}
	.pjx{	image{width: 40rpx;
	margin-left: 30rpx;
	height: 40rpx;}
		margin: 20rpx;
		border-radius: 0.5rem;
		background-color: white;}
	.pjz{
		margin: 20rpx;
		border-radius: 0.5rem;
		background-color: white;
	}
	.pjkz{
		margin: 20rpx;
		display: flex;
		justify-content: space-between;
	}
	.pjsr{
		
		image{width: 50rpx;
display:flex;
margin-bottom: 20rpx;
justify-content: center;
margin-left: 45%;

		height:50rpx;}
		input{padding-bottom: 200rpx;}
	}
	.pjzs{
		margin: 20rpx;
		display: flex;
		image{width: 100rpx;
	margin-right: 20rpx;
		height: 100rpx;}
	}
	.pjms{
		display: flex;
		margin: 20rpx;
		image{
			margin-left: 30rpx;
		width: 40rpx;
			height: 40rpx;
		}
	}
	.pjbty{
		p{color: white;
			border-radius: 1rem;
			padding: 10rpx 20rpx 10rpx 20rpx;
			background-color: #ff5500;
			margin-left: 300rpx;}
	}
	.pjbtz{
		align-items: center;
		p{padding-left: 30rpx;}
		padding: 30rpx;
		display: flex;
		image{width: 50rpx;
		height: 50rpx;}
	}
	.pjbt{
	
		display: flex;
			align-items: center;
	}
.beijing{
	height:100vh;
	background-color: #dcdcdc;
}
</style>
