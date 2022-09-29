<template>
	<view class="beijing">
		<view class="alldaohang">
			<view class="daohangs">
				
			
			<image src="../../static/heifanhui.png" mode="" style="height: 50rpx; width: 40rpx;"></image>
						<input class="uni-input" confirm-type="search">
		<image src="../../static/heigengduo.png" mode="" style="height: 50rpx; width: 40rpx;"></image>
		</view>
	<view class="jingang">
		<p>全部</p>
		<p>待付款</p>
		<p>待发货</p>
		<p>待收货</p>
		<p>待评价</p>
	</view>
		</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待发货</p>
			</view>
			<view class="xinxizhong1">
				<image src="../../static/zhuyeguanggao3.webp" mode=""></image>
				<view class="xinxizz">
		
					<p>这里是商品详情介绍</p>
					<p>尺码颜色</p>
					<p>规格</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
			<p>提醒发货</p>
			</view>
	</view>
	</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待发货</p>
			</view>
			<view class="xinxizhong1">
				<image src="../../static/zhuyeguanggao4.webp" mode=""></image>
				<view class="xinxizz">
		
			
			<p>这里是商品详情介绍</p>
			<p>尺码颜色</p>
			<p>规格</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
			<p>提醒发货</p>
			</view>
	</view>
	</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待发货</p>
			</view>
			<view class="xinxizhong1">
		<image src="../../static/zhuyeguanggao1.webp" mode=""></image>
				<view class="xinxizz">
		
			
			<p>这里是商品详情介绍</p>
			<p>尺码颜色</p>
			<p>规格</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
			<p>提醒发货</p>
			</view>
	</view>
	</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待发货</p>
			</view>
			<view class="xinxizhong1">
		<image src="../../static/zhuyeguanggao5.webp" mode=""></image>
				<view class="xinxizz">
		
				
				<p>这里是商品详情介绍</p>
				<p>尺码颜色</p>
				<p>规格</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
				<p>提醒发货</p>
			</view>
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
 .beijing{
			background-color: #f0f0f0;
 }
	.shangpinxxx{
		margin-top: 20rpx;
	view{display: flex;
	justify-content: space-between;}
	}
	.gouwuche {
		display: flex;
		justify-content: end;
		padding-right: 20rpx;
	
		p {
			padding-bottom: 5rpx;
			font-size: 25rpx;
			color: white;
			background-color: #ff5500;
			padding-left: 10rpx;
					padding-right: 10rpx;

			border-radius: 0.5rem;
		}
	
	
	}
	
	.shangpinxinxi {
		background-color: white;
		border-radius: 0.5rem;
		margin: 20rpx;
		padding: 20rpx;
	}
	
	.xinxizhong1 {
		display: flex;
		justify-content: space-between;
	
		image {
			width: 200rpx;
			height: 200rpx;
		}
	
		margin: 20rpx;
		padding: 20rpx;
	
	}
	
	.xinxishang {
		display: flex;
		justify-content: space-between;
		margin: 20rpx;
	
	}
	
	.jingang{
		border-radius: 0.5rem;
			padding: 20rpx;
		background-color: white;
		margin-top: 20rpx;
	display: flex;
	justify-content:space-around;
	}
	.daohangs{display: flex;}
	.uni-input{
	border-radius: 1rem;
	border: 5rpx solid orangered;
	margin-left: 40rpx;
	margin-right: 40rpx;
		width: 500rpx;
	}
.alldaohang{padding: 20rpx;

}
</style>
