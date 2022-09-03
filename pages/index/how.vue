<template>
	<view>
		<view class="input">
			<view class="anniu">
				<image class="anniu1" src="../../static/fanhui.png" mode=""></image>
				<P>今日爆款</P>
				<view class="anniu23">
					<image class="anniu2" src="../../static/fangdajing.png" mode=""></image>
					<image class="anniu3" src="../../static/gengduo.png" mode=""></image>
				</view>

			</view>
			<image class="zixun" src="../../static/咨询.png_.webp" mode=""></image>
		</view>
		<view class="jingangqu">

			<p class="">
				精选
			</p>
			<p class="">
				上新
			</p>
			<p class="">
				进口
			</p>
			<p class="">
				汽车
			</p>
			<p class="">
				文娱
			</p>
			<p class="">
				包饰
			</p>
			<p class="">
				保健
			</p>
		</view>
		<!-- 		<view class="poster">
<!-- 			<view class="poster1">
				<image class="image1" src="../../static/logo.png" mode=""></image>
				<p class="wenzi1">2.2磅乳清蛋白粉</p>
				<view class="image234">
					<image class="image2" src="../../static/logo.png" mode=""></image>
					<image class="image3" src="../../static/logo.png" mode=""></image>
					<image class="image4" src="../../static/logo.png" mode=""></image>
				</view>
				<view class="jiaqian">


					<p class="wenzi2">已售2w</p>
					<view class="wenzi3">
						<p>￥</p>
						<p>140</p>
						<p>补贴后</p>
						<p>￥220</p>
					</view>
				</view>
				<image src="../../static/qianggou.png" mode=""></image>

			</view> -->
	<view class="box">
		<image src="../../static/logo.png" mode=""></image>
		<view class="box-right">
			<p>2.2蛋白粉</p>
			<view class="wenzizuhe">
				<p>买贵必赔</p>
				<p>保税仓发货</p>
				<p>限购一件</p>
			</view>
			<p>已售两万</p>
			<p>140补贴后</p>
			<view class="juan">
				<view class="juan-left">
					<p>补贴券</p>
					<p>￥80</p>
				</view>
				<view class="juan-right">
					<p>去抢券下单</p>
				</view>
			</view>
		</view>

	</view>
	<view class="box">
		<image src="../../static/logo.png" mode=""></image>
		<view class="box-right">
			<p>2.2蛋白粉</p>
			<view class="wenzizuhe">
				<p>买贵必赔</p>
				<p>保税仓发货</p>
				<p>限购一件</p>
			</view>
			<p>已售两万</p>
			<p>140补贴后</p>
			<view class="juan">
				<view class="juan-left">
					<p>补贴券</p>
					<p>￥80</p>
				</view>
				<view class="juan-right">
					<p>去抢券下单</p>
				</view>
			</view>
		</view>

	</view>
	<view class="box">
		<image src="../../static/logo.png" mode=""></image>
		<view class="box-right">
			<p>2.2蛋白粉</p>
			<view class="wenzizuhe">
				<p>买贵必赔</p>
				<p>保税仓发货</p>
				<p>限购一件</p>
			</view>
			<p>已售两万</p>
			<p>140补贴后</p>
			<view class="juan">
				<view class="juan-left">
					<p>补贴券</p>
					<p>￥80</p>
				</view>
				<view class="juan-right">
					<p>去抢券下单</p>
				</view>
			</view>
		</view>
	
	</view>
	</view>



</template>
<style lang="scss">
	.juan{
		display: flex;
		background-image:url("../../static/qianggou.png");
	background-size:100%
	}
	.box{
		padding: 20rpx;
		display: flex;
		image{width: 300rpx;
		height: 300rpx;
		margin-right: 20rpx;}
		.wenzizuhe{
			display: flex;
			font-size: 20rpx;
		}
	}
	.input {
		border: 1px solid red;
		background-image: url("../../static/baokuanbj.jpg");
		background-size: contain;
		background-repeat: no-repeat;
		width: 100%;
		height: 600rpx;
		display: flex;

		.anniu1 {

			width: 80rpx;
			height: 50rpx;
		}

		p {
			color: white;


		}

		.anniu2 {
			display: flex;
			width: 60rpx;
			height: 50rpx;


		}

		.anniu3 {

			width: 60rpx;
			height: 20rpx;


		}

		.anniu23 {
			display: flex;
			justify-content: flex-end;


		}

		.anniu {
			width: 100%;
			border: 1px solid yellow;
			display: flex;


		}

		.zixun {
			position: absolute;
			height: 130rpx;
			width: 100%;
			top: 450rpx;
		}
	}

	.jingangqu {
		display: flex;




		p {
			display: flex;
			font-size: 30rpx;
			margin-left: 45rpx;

		}

	}

	.poster>.poster1 {



		.jiaqian {
			.wenzi2 {
				position: absolute;
				left: 45%;
				top: 50%
			}
		}

	}
</style>
