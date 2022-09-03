<template>
	<view>
	<view class="daohang">
		<view class="fanhui">
			<image src="../../static/heifanhui.png" mode=""></image>
			<p>|</p>
			<image src="../../static/heigengduo.png" mode=""></image>
		</view>
	<view class="shuru">
		<p>商品</p>
			<input class="uni-input" confirm-type="search" />
	<view class="sou">
		搜索
	</view>
	</view>
	</view>
		<view class="xuanxiangshang">
			<p>搜索发现</p>
		<image src="../../static/yanjing.png" mode=""></image>
		</view>
		<view class="xuanxiangquxia">
			<p>xxx</p>
			<p>xxx</p>
			<p>xxx</p>
			<p>xxx</p>
			<p>xxx</p>
			<p>xxx</p>
			<p>xxx</p>
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
	.xuanxiangquxia{
		display: flex;
		justify-content:space-around;
p{border-radius: 0.5rem;
padding: 5rpx;
background-color: #f7f7f7;
}
	}
	.xuanxiangshang{
		display: flex;
		justify-content: space-between;
		margin-top: 60rpx;
		margin-left: 20rpx;
		margin-right: 20rpx;
	image{width:50rpx;
	height: 40rpx;}	
	}
	.shuru{display: flex;
	align-items: center;
	margin:20rpx;
	border:solid 1px red;
	background-color: #f7f7f7;
	border-radius: 1rem;
	p{padding-left: 20rpx;
	width: 70rpx;}
	}
	.uni-input{width: 280rpx;
	height: 70rpx;}
	.sou{
		display: flex;
		justify-content: center;
		align-items: center;
		width: 120rpx;
		height: 70rpx;
		color: white;
		border-radius: 1rem;


		    background-image: linear-gradient(-15deg,#ff5000,#ff6900 61%,#ff963f);
	}
	.daohang{
		display: flex;
		align-items: center;
	}
	.fanhui{
		width:170rpx;
		height: 70rpx;
		border: 1px solid black;
	 border-radius: 1rem;
		margin:20rpx;
		display: flex;
		align-items: center;
		image{
		width: 45rpx;
		height: 45rpx;
		margin-left: 20rpx;
		margin-right: 20rpx;
	}}
</style>
