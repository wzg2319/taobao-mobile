<template>
	<view>
		<view class="Navigation">
			<view class="home">
				<image mode="widthFix" src="../../static/taobaologo.png"></image>
			</view>
			<view class="sousuo">
				<view class="input">
					<input class="uni-input" confirm-type="search">
				</view>
				<view class="button">
					搜索
				</view>
			</view>

			<view class="qiandao">
				<image src="../../static/qiandao.png" mode=""></image>
			</view>
		</view>
		<view class="advertise">
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>天猫新品</p>
			</view>
			<view @click="test" class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>今日爆款</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>天猫国际</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>飞猪旅行</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>天猫超市</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>淘宝吃货</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>省钱卡</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>领淘金币</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>阿里拍卖</p>
			</view>
			<view class="">
				<image src="../../static/logo.png" mode=""></image>
				<p>分类</p>
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
	export default{
		methods:{
			test(){
				uni.navigateTo({
					url: 'how'
				});
				console.log('run')
			}
		}
	}
</script>


<style lang="scss">
	.Navigation {
		display: flex;
		background-color:#f4f4f4 ;
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

	.uni-input {
		width: 300rpx;
		height: 60rpx;
	}

	.button {
		text-align: center;
		margin: 8rpx;
		border: 1px solid red;
		color: white;
		background: linear-gradient(to right, #FF8D0E, #FF5000);
		border-radius: 1.5rem;
		width: 100rpx;



	}

	.home {
		image {
			margin: 30rpx;
			width: 110rpx;
		}
	}

	.qiandao image {

		width: 70rpx;
		height: 70rpx;
		margin-top: 20rpx
	}

	.advertise {

		display: flex;
		flex-wrap: wrap;
		justify-content: center;
margin:20rpx;
font-size: 30rpx;
		image {
			width: 100rpx;
			height: 100rpx;
			margin-top: 20rpx;
			margin-left: 20rpx;
			margin-right: 20rpx;

		}

		text-align: center;
	}

	.title {
		display: flex;
		flex-wrap: wrap;
		margin-left: 20rpx;

		p {
			background-color: red;
			border-radius: 0.1rem;




		}

	}

	.poster {
		image {
			width: 150rpx;
			height: 150rpx;
			margin-left: 20rpx
		}

	}


	.all {
		display: flex;
		flex-wrap: wrap;
	}

	.sousuo {
		display: flex;
		margin: 20rpx;
		border: 1px solid red;
		border-radius: 2rem;
	}

</style>
