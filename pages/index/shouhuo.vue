<template>
	<view class="beijing">
		<view class="header">
			<image src="../../static/heifanhui.png" mode="" style="width: 40rpx;
height: 40rpx;"></image>
			<view class="zhong">
				<p>卖家已发货</p>
				<p>剩余时间</p>
			</view>
			<view class="you">
				<image src="../../static/heigengduo.png" mode="" style="width: 40rpx;
height: 25rpx;"></image>
			</view>

		</view>
		<view class="ztpj">
			
		
		<view class="dqj">
			<view class="dqjz">
				<p>代取件</p>
				<p>09-09  0101</p>
			</view>
		<view class="dqjy">
			<p>详细信息</p>
		</view>
		</view>
	<view class="dqjdz">
		<p>地址地址地址地址</p>
		<p>详细地址</p>
		<p>取件码</p>
	</view>
	<view class="song">
		<p>送至 北京 中南海</p>
		<p>啊习收 号码我不知道</p>
	</view>
</view>
	<view class="shangpinxinxi">
		<view class="xinxishang">
			<p>店铺名称</p>
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
			<p>退款</p>
		</view>
		<view class="shangpinxxx">
			<view class="">
				<p>商品总价</p>
				<p>￥000</p>
			</view>
			<view class="">
				<p>商品总价</p>
				<p>￥000</p>
			</view>
			<view class="">
				<p>商品总价</p>
				<p>￥000</p>
			</view>
			<view class="">
				<p>商品总价</p>
				<p>￥000</p>
			</view>
			<view class="">
				<p>商品总价</p>
				<p>￥000</p>
			</view>
		</view>
	</view>
	<view class="zuixia">
		<view class="zuixiazuo">
				<p>更多</p>	
		</view>
	<view class="zuixiayou">
		<p>修改地址</p>
		<p>找朋友付</p>
		<p>继续付款</p>
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
		margin: 20rpx;
	}
	.zuixiayou{p{border:  1px solid black;
	border-radius: 0.5rem;
	padding: 10rpx;
	margin-right: 20rpx;}
	display: flex;
		justify-content: end;
		margin-left: 170rpx;
	}
	.zuixia{
		padding-top:20rpx;
		display: flex;
		align-items: center;
		background-color: white;}
	.shangpinxxx{
		margin-top: 20rpx;
	view{display: flex;
	justify-content: space-between;}
	}
	
	
	
	.song{margin-left: 50rpx;
	padding-bottom: 20rpx;}
	.ztpj{
		background-color: white;
		border-radius: 0.5rem;
		margin: 20rpx;
	}
	.dqjdz{
		margin: 50rpx;
		padding: 20rpx;
		background-color: #e1e1e1;
		border-radius: 0.5rem;
	}
	.dqjz{p{padding-right: 20rpx;}
	margin: 20rpx;
		display: flex;
	}
	.dqj{display: flex;
	color: #ff5500;
	align-items: center;}
	.dqjy{
		margin-left: 200rpx;
	}
	.beijing{
		background-color: #e1e1e1;
	}
	.zhong {
		padding-left: 20rpx;
		color: black;
		text-align: center;
	}
	
	.you {
		padding-left: 400rpx;
	}
	.header {
		padding: 20rpx;
		display: flex;
		align-items: center;


	}
</style>
