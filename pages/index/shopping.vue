<template>
	<view>
		<view class="header">
			<p>购物车</p>
			<p>管理</p>
		</view>
		<p>共33件宝贝</p>


		<view v-for="(item,index) in items" class="yeqian" :key="index"> 
			<view class="biaoti">
				<view class="biaotizuo">
					<image src="../../static/xuanze.webp" mode=""></image>
					{{item.title}}

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
					<p>{{item.details}}</p>
					<p>{{item.color}}尺码</p>
					<view class="mainyouxia">
						<p>￥{{item.nums}}</p>
						<p>数量</p>
					</view>
				</view>
				
				<view @click="deleteView(index)">
					删除
				</view>
			</view>

		</view>
		<view class="nav">
<image src="../../static/qiandao.png" mode="" @click="index"></image>

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
	export default {
		created() {
			this.showList()
		},
		watch:{
			nums(){
			this.showList()
			const storageShop = uni.getStorageSync('shop')
			uni.showToast({
				title: `删除购物车成功,您有${storageShop}件商品在购物车内`,
				duration: 2000
			});
			}
		},
		data() {
			return {
				items: [],
				nums:0
			}
		},
		methods: {
	index(){
		uni.navigateTo({
			url: 'index'
		});
	},
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
				},
			deleteView(index){
				const storageShop = uni.getStorageSync('shop')
				this.nums = storageShop !== 0 ? storageShop - 1 : 0
				uni.setStorageSync('shop',this.nums)
			},
			showList(){
				const fakeShop = {
							title: '飞科专卖店',
							image: '',
							nums: '99',
							details: '详情描述',
							color: 'black'
						}
				let arr = []
				const storageShop = uni.getStorageSync('shop')
				if (storageShop) {
					for(let i = 0; i < storageShop; i++){
						arr.push(fakeShop)
					}
				}
				this.items = arr
			}
		},

	}
</script>

<style lang="scss">
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
