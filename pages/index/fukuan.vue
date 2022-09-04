<template>
	<view class="beijing">
		<view class="header">
			<image src="../../static/fanhui.png" mode="" style="width: 40rpx;
height: 40rpx;"></image>
			<view class="zhong">
				<p>等待买家付款</p>
				<p>剩余时间</p>
			</view>
			<view class="you">
				<image src="../../static/gengduo.png" mode="" style="width: 40rpx;
height: 15rpx;"></image>
			</view>

		</view>



		<view class="gerenxinxi">
			<view class="gerenxinxizuo">
				<image src="../../static/logo.png" mode=""></image>
			</view>
			<view class="gerenxinxizhong">
				<p>xxx xxx xxx xxx xxx</p>
				<p>xxx xxx xxx xxx xxx</p>
			</view>
			<view class="gerenxinxiyou">
				<p>修改</p>
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
				<p>加入购物车</p>
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

	.gerenxinxizhong {
		padding-left: 20rpx;
	}

	.gerenxinxiyou {
		border-radius: 1rem;
		border: 1px solid #c7c7c7;
		display: flex;
		justify-content: end;
		margin-left: 250rpx;
		padding: 10rpx;
	}

	.beijing {
		background-color: #c7c7c7;
	}

	.gerenxinxi {
		padding: 20rpx;
		display: flex;
		background-color: white;
		border-radius: 0.5rem;
		align-items: center;

		image {
			width: 30rpx;
			height: 30rpx;
		}

		margin: 20rpx;
	}

	.zhong {
		padding-left: 20rpx;
		color: white;
		text-align: center;
	}

	.you {
		padding-left: 400rpx;
	}

	.header {
		padding: 20rpx;
		display: flex;
		align-items: center;
		background-color: #c72e0f;

	}
</style>
