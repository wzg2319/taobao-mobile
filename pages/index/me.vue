<template>
	<view>
		<view class="xinxi">
			<image class="touxiang" src="../../static/qiandao.png" mode=""></image>
			<view class="xinxizhong">
<p>我的淘宝昵称</p>
				<p>账号名称</p>
			</view>
			<view class="xinxiyou">
				<image src="../../static/shezhi.png" mode=""></image>
			</view>
		</view>
		<view class="xuanxiang">
			<view class="xuanxiangzuo">
				<image src="../../static/shoucang.png" mode=""></image>
			<p>收藏</p>
			</view>
			<view class="xuanxiangzhong">
				<image src="../../static/dingyue.png" mode=""></image>
			<p>订阅</p>
			</view>
			<view class="xuanxiangyou">
				<image src="../../static/zuji.png" mode=""></image>
			<p>足迹</p>
			</view>
		</view>
	<view class="dingdan">
		<view class="biaoti">
			<p>我的订单</p>
			<p>全部</p>
		</view>
		<view class="ddxuanxiang">
			<view class="">
				<image src="../../static/fukuan.png" mode=""></image>
			<p>待付款</p>
			</view>
			<view class="">
				<image src="../../static/fahuo.png" mode=""></image>
			<p>待发货</p>
			</view>
			<view class="">
				<image src="../../static/shouhuo.png" mode=""></image>
			<p>待收货</p>
			</view>
		<view class="">
			<image src="../../static/pingjia.png" mode=""></image>
		<p>待评价</p>
			</view>
		<view class="">
			<image src="../../static/shouhou.png" mode=""></image>
		<p>待售后</p>
	
		</view>
		</view>
	</view>
	<view class="gongju">
		<view class="top">
				<p>我的工具</p>
		</view>
		<view class="gongjuxia">
			
		
		<view class="">
			<image src="../../static/kefu.png" mode=""></image>
			<p>官方客服</p>
		</view>
		<view class="">
			<image src="../../static/shiyong.png" mode=""></image>
			<p>试用领取</p>
		</view>
		<view class="">
			<image src="../../static/huiyuan.png" mode=""></image>
			<p>店铺会员</p>
		</view>
		</view>
	</view>
	<view class="nav">
	<image src="../../static/qiandao.png" mode=""></image>
	
				<view>
					<image src="../../static/购物车空.png" mode=""></image>
					<p>购物车</p>
				</view>
	
				<view @click="test2">
					<image mode="widthFix" src="../../static/logo.png"></image>
					<p>我的</p>
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
	.gongju{
		
		margin: 20rpx;
		padding: 20rpx;
		image{
			
			width: 80rpx;
			height: 80rpx;
		}
		.gongjuxia{
				display: flex;
				justify-content: space-around;
					text-align: center;
			
		}
}
	.ddxuanxiang{
		display: flex;
		justify-content: space-around;
		image{width: 60rpx;
		height: 60rpx;}
		text-align: center;
	}
	.biaoti{
		margin: 20rpx;
		padding: 20rpx;
		display: flex;
		justify-content: space-between;
	}
	.xuanxiang{
		display: flex;
		justify-content: space-around;
			text-align: center;
		image{
			width: 80rpx;
			height: 80rpx;
		}
	}
.xinxi{
padding: 20rpx;
	display: flex;
	justify-content: space-between;
	.touxiang{width: 100rpx;
	height: 100rpx;}
	.xinxiyou{
		image{
		width: 60rpx;
		height: 60rpx;}
	}
}
	.nav {
		box-sizing: border-box;
	position: fixed;
	bottom: 0rpx;
	width: 100vw;
		border: 1px solid red;
		display: flex;
		justify-content: space-around;
		text-align: center;


align-items: center;
		image {
			width: 80rpx;
			height: 80rpx;
		}
	}
</style>
