<template>
	<view>
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
				<p>店铺名称</p><p>待评价</p>
			</view>
			<view class="xinxizhong1">
				<image src="../../static/logo.png" mode=""></image>
				<view class="xinxizz">
		
					<p>xxxxxxxxx</p>
					<p>xxxxxxx</p>
					<p>xxxxxxx</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
				<p>待评价</p>
			</view>
	</view>
	</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待评价</p>
			</view>
			<view class="xinxizhong1">
				<image src="../../static/logo.png" mode=""></image>
				<view class="xinxizz">
		
					<p>xxxxxxxxx</p>
					<p>xxxxxxx</p>
					<p>xxxxxxx</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
				<p>待评价</p>
			</view>
	</view>
	</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待评价</p>
			</view>
			<view class="xinxizhong1">
				<image src="../../static/logo.png" mode=""></image>
				<view class="xinxizz">
		
					<p>xxxxxxxxx</p>
					<p>xxxxxxx</p>
					<p>xxxxxxx</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
				<p>待评价</p>
			</view>
	</view>
	</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待评价</p>
			</view>
			<view class="xinxizhong1">
				<image src="../../static/logo.png" mode=""></image>
				<view class="xinxizz">
		
					<p>xxxxxxxxx</p>
					<p>xxxxxxx</p>
					<p>xxxxxxx</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
				<p>待评价</p>
			</view>
	</view>
	</view>
	<view class="shangpin">
		<view class="shangpinxinxi">
			<view class="xinxishang">
				<p>店铺名称</p><p>待评价</p>
			</view>
			<view class="xinxizhong1">
				<image src="../../static/logo.png" mode=""></image>
				<view class="xinxizz">
		
					<p>xxxxxxxxx</p>
					<p>xxxxxxx</p>
					<p>xxxxxxx</p>
				</view>
				<view class="xinxizy">
					<p>￥999</p>
					<p>*1</p>
				</view>
			</view>
			<view class="gouwuche">
				<p>待评价</p>
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
	.shangpinxxx{
		margin-top: 20rpx;
	view{display: flex;
	justify-content: space-between;}
	}
	.gouwuche {
		display: flex;
		justify-content: end;
	
		p {
			border: 1px solid black;
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
	
	.jingang{margin: 50rpx;
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
.alldaohang{margin: 20rpx;

}
</style>
