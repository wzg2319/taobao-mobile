<template>
	<view>
		<view class="header">
			<p>购物车</p>
			<p>管理</p>
		</view>
		<p>共33件宝贝</p>
		<view class="yeqian">
			<view class="biaoti">
				<view class="biaotizuo">
					<image src="../../static/xuanze.webp" mode=""></image>
					xxx专卖店

				</view>
				<view class="biaotiyou">
					领券
				</view>
			</view>
			<view class="main">
				<view class="mainzuo">
					<image class="zuo1" src="../../static/xuanze.webp" mode=""></image>
					<image class="zuo2" src="../../static/logo.png" mode=""></image>
				</view>
				<view class="mainyou">
					<p>商品的详细描述</p>
					<p>颜色尺码</p>
					<view class="mainyouxia">
						<p>￥99</p>
						<p>数量</p>
					</view>
				</view>
			</view>


		</view>
		<view class="yeqian">
			<view class="biaoti">
				<view class="biaotizuo">
					<image src="../../static/xuanze.webp" mode=""></image>
					xxx专卖店
		
				</view>
				<view class="biaotiyou">
					领券
				</view>
			</view>
			<view class="main">
				<view class="mainzuo">
					<image class="zuo1" src="../../static/xuanze.webp" mode=""></image>
					<image class="zuo2" src="../../static/logo.png" mode=""></image>
				</view>
				<view class="mainyou">
					<p>商品的详细描述</p>
					<p>颜色尺码</p>
					<view class="mainyouxia">
						<p>￥99</p>
						<p>数量</p>
					</view>
				</view>
			</view>
		
		
		</view>
		<view class="yeqian">
			<view class="biaoti">
				<view class="biaotizuo">
					<image src="../../static/xuanze.webp" mode=""></image>
					xxx专卖店
		
				</view>
				<view class="biaotiyou">
					领券
				</view>
			</view>
			<view class="main">
				<view class="mainzuo">
					<image class="zuo1" src="../../static/xuanze.webp" mode=""></image>
					<image class="zuo2" src="../../static/logo.png" mode=""></image>
				</view>
				<view class="mainyou">
					<p>商品的详细描述</p>
					<p>颜色尺码</p>
					<view class="mainyouxia">
						<p>￥99</p>
						<p>数量</p>
					</view>
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
	
	.main {
		display: flex;
	}

	.mainyou {
		margin: 20rpx;
	}

	.mainyouxia {
		display: flex;
				align-items: flex-end;
		justify-content: space-between;

	}

	.mainzuo {
		display: flex;
		align-items: center;
	}

	.zuo1 {
		width: 45rpx;
		height: 45rpx;
		margin: 30rpx;
	}

	.zuo2 {
		width: 200rpx;
		height: 200rpx;
		margin-top: 30rpx;
	}

	.biaoti {
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin-top: 100rpx;
		margin-left: 20rpx;
		margin-right: 20rpx;

		image {
			width: 45rpx;
			height: 45rpx;
		}
	}

	.header {
		padding: 20rpx;
		display: flex;
		justify-content: space-between;
	}
</style>
