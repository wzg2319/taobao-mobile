<template>
	<view class="beijing">
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
				<image src="../../static/tianmaoxinpin.webp" mode=""></image>
				<p>天猫新品</p>
			</view>
			<view @click="toPath" class="">
			<image src="../../static/jinribaokuan.webp" mode=""></image>
				<p>{{ name }}</p>
			</view>
			<view class="">
				<image src="../../static/tianmaoguoji.webp" mode=""></image>
				<p>天猫国际</p>
			</view>
			<view class="">
				<image src="../../static/feizhulvxing.webp" mode=""></image>
				<p>飞猪旅行</p>
			</view>
			<view class="">
				<image src="../../static/tianmaochaoshi.webp" mode=""></image>
				<p>天猫超市</p>
			</view>
			<view class="">
			<image src="../../static/taobaochihuo.webp" mode=""></image>
				<p>淘宝吃货</p>
			</view>
			<view class="">
				<image src="../../static/shengqianka.webp" mode=""></image>
				<p>省钱卡</p>
			</view>
			<view class="">
			<image src="../../static/lingtaojinbi.webp" mode=""></image>
				<p>领淘金币</p>
			</view>
			<view class="">
			<image src="../../static/alipaimai.webp" mode=""></image>
				<p>阿里拍卖</p>
			</view>
			<view class="">
				<image src="../../static/分类.webp" mode=""></image>
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
					<image src="../../static/tiantiantemai1.webp" mode=""></image>
					<image src="../../static/tiantiantemai2.webp" mode=""></image>
				</view>
			</view>
			<view class="region">
				<view class="title">
					每日好店
					<p>特色</p>
				</view>
				<view class="poster">
					<image src="../../static/meirihaodian1.webp" mode=""></image>
					<image src="../../static/meirihaodian2.webp" mode=""></image>
				</view>
			</view>

			<view class="region">
				<view class="title">
					天天特卖
					<p>1元秒杀</p>
				</view>
				<view class="poster">
					<image src="../../static/tiantiantemai1.webp" mode=""></image>
					<image src="../../static/tiantiantemai2.webp" mode=""></image>
				</view>
			</view>

			<view class="region">
				<view class="title">
					有好货
					<p>好口碑</p>
				</view>
				<view class="poster">
					<image src="../../static/youhaohuo1.webp" mode=""></image>
					<image src="../../static/youhaohuo2.webp" mode=""></image>
				</view>
			</view>

		</view>
		<view class="jihe">
			
		
<view class="guanggaoqu" @click="details">
<image src="../../static/zhuyeguanggao1.webp" mode=""></image>
<p>这里是商品详情介绍</p>
<p>￥9999</p>
	
</view>
<view class="guanggaoqu" @click="details">
<image src="../../static/zhuyeguanggao2.webp" mode=""></image>
<p>这里是商品详情介绍</p>
<p>￥9999</p>
	
</view>
</view>
		<view class="jihe">
					
				
		<view class="guanggaoqu" @click="details" >
<image src="../../static/zhuyeguanggao3.webp" mode=""></image>
		<p>这里是商品详情介绍</p>
		<p>￥9999</p>
			
		</view>
		<view class="guanggaoqu" @click="details">
<image src="../../static/zhuyeguanggao4.webp" mode=""></image>
		<p>这里是商品详情介绍</p>
		<p>￥9999</p>
			
		</view>
		</view>
		<view class="jihe">
					
				
		<view class="guanggaoqu" @click="details">
<image src="../../static/zhuyeguanggao5.webp" mode=""></image>
		<p>这里是商品详情介绍</p>
		<p>￥9999</p>
			
		</view>
		<view class="guanggaoqu" @click="details">
<image src="../../static/zhuyeguanggao6.webp" mode=""></image>
		<p>这里是商品详情介绍</p>
		<p>￥9999</p>
			
		</view>
		</view>
		<view class="nav">
<image src="../../static/qiandao.png" mode=""></image>

			<view @click="shopcar">
				<image src="../../static/购物车空.png" mode=""></image>
				<p>购物车</p>
			</view>

			<view @click="test2">
				<image src="../../static/me.png" mode=""></image>
				<p>我的</p>
			</view>
		</view>

	</view>
</template>




<script>
	export default{
		data(){
			return{
				name:'今日爆款'
			}
		},

		
		methods:{
		details(){
			uni.navigateTo({
				url: 'spxiangqing'
			});
		},
			shopcar(){
				uni.navigateTo({
					url: 'shopping'
				});
			},
			test2(){
				uni.navigateTo({
					url: 'me'
				});
			},
			toPath(a){
				uni.navigateTo({
					url: 'how'
				});
			}
		}
	}
</script>





<style lang="scss">
	.beijing{background-color:#f4f4f4 ;}
	.jihe{
		p{font-size: 25rpx;
			margin:10rpx}
		display: flex;
	justify-content: space-around;}
	.guanggaoqu{background-color: white;
	border-radius: 0.5rem;
	margin: 20rpx;
	image{	border-radius: 0.5rem;
		width: 300rpx;
	height: 300rpx;}
		
	}
	.Navigation {
		display: flex;
		background-color:#f4f4f4 ;
	}

	.nav {
P{font-size: 30rpx
;}
		background-color: white;
		box-sizing: border-box;
	position: fixed;
	bottom: 0rpx;
	width: 100vw;
		display: flex;
		justify-content: space-around;
		text-align: center;


align-items: center;

		image {
			padding-top: 20rpx;
			width: 50rpx;
			height: 50rpx;
		}
	}

	.uni-input {
		padding-left: 20rpx;
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
background-color: white;
padding: 10rpx;
border-radius: 0.5rem;
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
margin:20rpx;
font-size: 30rpx;
		image {
			width: 130rpx;
			height: 100rpx;

		}

		text-align: center;
	}

	.title {
		display: flex;
		flex-wrap: wrap;
		margin-left: 20rpx;

		p {
			padding-left: 10rpx;
					padding-right: 10rpx;
			margin-left: 20rpx;
			border-radius: 0.5rem;
			background-color: #ff4200;
			color: white;
			font-size: 30rpx;




		}

	}

	.poster {
		image {
			width: 150rpx;
			height: 150rpx;
margin-left: 20rpx;

		}

	}


	.all {
		padding-top: 30rpx;
		border-radius: 0.5rem;
		margin: 20rpx;
		background-color: white;
		display: flex;
		justify-content: space-around;
		flex-wrap: wrap;
	}

	.sousuo {
		display: flex;
		margin: 20rpx;
		border: 1px solid red;
		border-radius: 2rem;
	}

</style>
