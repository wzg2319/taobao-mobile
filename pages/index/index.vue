<template>
	<view>
		<view class="Navigation">
			<view class="home">
				<image src="../../static/logo.png" mode=""></image>
			</view>
			<view class="input">
				<input class="uni-input" confirm-type="search">
			</view>
			<view class="button">
				搜索
			</view>
			<view class="qiandao">
				<image src="../../static/logo.png" mode=""></image>
			</view>
		</view>
		<view class="advertise">
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		 <view class="">
		 	<image src="../../static/logo.png" mode=""></image>
		 			<p>111</p>
		 </view>
		</view>
		<view class="all">
			
		
		<view class="region">
			<view class="title">
			聚划算
			<p>品牌折扣</p>
</view>
			<view class="poster">
			<image src="../../static/logo.png" mode=""></image>
			<image src="../../static/logo.png" mode=""></image>
			</view>
		</view>
		<view class="region">
					<view class="title">
					每日好店
					<p>特色</p>
		</view>
					<view class="poster">
					<image src="../../static/logo.png" mode=""></image>
					<image src="../../static/logo.png" mode=""></image>
					</view>
				</view>
		
		<view class="region">
					<view class="title">
					天天特卖
					<p>1元秒杀</p>
		</view>
					<view class="poster">
					<image src="../../static/logo.png" mode=""></image>
					<image src="../../static/logo.png" mode=""></image>
					</view>
				</view>
		
		<view class="region">
					<view class="title">
					有好货
					<p>好口碑</p>
		</view>
					<view class="poster">
					<image src="../../static/logo.png" mode=""></image>
					<image src="../../static/logo.png" mode=""></image>
					</view>
				</view>
		
</view>

		<view class="nav">
			<image mode="widthFix" src="../../static/logo.png"></image>

			<view>
				<image mode="widthFix" src="../../static/logo.png"></image>
				<p>购物车</p>
			</view>

			<view>
				<image mode="widthFix" src="../../static/logo.png"></image>
				<p>我的</p>
			</view>
		</view>

	</view>
</template>



<style lang="scss">
	.Navigation {
		display: flex;

	}

	.nav {
		border: 1px solid red;
		display: flex;
		justify-content: space-around;
		text-align: center;

		image {
			width: 100rpx;
		}
	}

	.uni-input {
		border: 1px solid red;
		width: 400rpx;
	}

	.button {
		border: 1px solid red;
background-color: #f0f8ff;
width: 80rpx;
height: 40rpx;
font-size: 30rpx;
	}

	.home {
		image {
			width: 100rpx;
			height: 100rpx;
		}
	}
	.qiandao
	image{
		width: 100rpx;
		height: 100rpx;
	}
	.advertise{
		display: flex;
		flex-wrap: wrap;
		image{
			width: 100rpx;
			height: 100rpx;
			margin:20rpx;
			
		}
		text-align: center;
	}
	.title{
		display: flex;
		flex-wrap: wrap;
		margin-left: 20rpx;
		p{
			background-color: red;
		}
		
	}
	.poster{
		image{
			width: 150rpx;
			height: 150rpx;
			margin-left: 20rpx
		}

		}

	
	.all{
		display: flex;
		flex-wrap: wrap;
	}
</style>
