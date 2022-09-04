<template>
	<view class="zong">
		<view class="daohang">
			<image src="../../static/heifanhui.png" mode=""></image>
			<view class="biaodan">
				<image src="../../static/heifangdajing.png" mode=""></image>
				<input class="uni-input" confirm-type="search" />

			</view>
			<image src="../../static/qianjin.png" mode=""></image>
			<image src="../../static/购物车空.png" mode=""></image>
			<image src="../../static/heigengduo.png" mode=""></image>
		</view>
		<view class="gundong">
			<image src="../../static/logo.png" mode=""></image>
		</view>
		<view class="xiangqing">
			<p class="biaojia">
				￥999
			</p>
			<p>这里是商品的大概简介</p>
			<view class="xiangqingxia">
				<p>推荐</p>
				<p>帮我选</p>
				<p>分享</p>
			</view>
		</view>
		<view class="dizhi">
			<view class="dizhishang">
				<view class="dizhizuo">
					<p>发货</p>
					<p>地址</p>
					<p>快递：免运费</p>
				</view>

				<view class="dizhiyou">
					月销1w+
				</view>
			</view>

			<view class="dizhixia">
				<p>保障</p>
				<p>七天无理由</p>
			</view>
		</view>
		<view class="pingjia">
			<view class="pjs">
				<p>宝贝评价</p>
				<view class="" style="color: #ff5500;">
					查看全部
				</view>
			</view>
			<view class="wendajia">
				<p>问大家</p>
				<view class="" style="color: #ff5500;">
					查看全部
				</view>
			</view>
		</view>
		<view class="shangjia">
			<view class="shangjiashang">
				<view class="">
						<image src="../../static/logo.png" mode="" style="width: 80rpx; height: 80rpx;"></image>
					</view>
					<p>商家名称</p>
				
				<view class="shangjiayou">
					<p>宝贝描述</p>
					<p>卖家服务</p>
					<p>物流服务</p>
				</view>
			</view>
		
		<view class="shangjiaxia">
			<view style="margin-right: 10rpx; padding: 10rpx;">进店逛逛</view>
			<view style="margin-left: 10rpx; padding: 10rpx;">全部宝贝</view>
		</view>
		</view>
	<view class="xiabu">
		<view class="xiabuzuo">
			<view class="dianpu">
						<image src="../../static/logo.png" mode=""></image>
					<p>店铺</p>
					</view>
					<view class="kefu">
			<image src="../../static/logo.png" mode=""></image>			
					<p>客服</p>
					</view>
				<view class="shoucang">
					<image src="../../static/logo.png" mode=""></image>
							<p>收藏</p>
				</view>
		</view>
		
	<view class="xiabuyou">
		<p>加入购物车</p>
		<p>立即购买</p>
	</view>
	</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {left

			}
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.xiabuyou{
		background-color: #ff5500;

		border-radius: 1rem;
		p{padding: 20rpx;
		color: white;}
		display: flex;
		
	}
	.xiabuzuo{
		font-size: 20rpx;
		
		display: flex;
		image{margin-right: 50rpx;
		width: 50rpx;
		height: 50rpx;

	}
		
	}
	.xiabu{

		display: flex;
		align-items: center;
		padding: 20rpx;
		margin: 20rpx;
			background-color: white;
			border-radius: 0.5rem;
	}
	.shangjiaxia{
		display: flex;
view{border: 1px solid red;
border-radius: 1rem;
}
		justify-content: center;
	
	}
	.shangjiayou{
		padding-left: 270rpx;
	}
	.shangjiashang{
		display:flex;
		margin: 20rpx;
		p{padding-left:20rpx;}
	}
	.shangjia{padding: 20rpx;
	margin: 20rpx;
		background-color: white;
		border-radius: 0.5rem;
	}
	.pingjia {

		background-color: white;
		border-radius: 0.5rem;
		margin: 20rpx;
	}

	.wendajia {
		display: flex;
		justify-content: space-between;
		margin: 20rpx;
	}

	.pjs {

		display: flex;
		justify-content: space-between;
		margin: 20rpx;
	}

	.dizhixia {
		margin: 20rpx;
		display: flex;
	}

	.dizhishang {
		margin: 20rpx;
		display: flex;

		.dizhiyou {
			display: flex;
			justify-content: flex-end;
			padding-left: 130rpx;
		}
	}

	.dizhi {

		background-color: white;
		border-radius: 0.5rem;
		margin: 20rpx;
	}

	.dizhizuo {
		display: flex;

		p {
			padding-right: 30rpx;
		}
	}

	.xiangqing {


		background-color: white;
		border-radius: 0.5rem;
		margin: 20rpx;

		p {
			padding: 20rpx;
		}
	}

	.xiangqingxia {
		padding: 20rpx;
		display: flex;
		justify-content: space-around
	}

	.gundong {
		display: flex;
		justify-content: center;
		image{
		width: 300rpx;	
		height: 300rpx;
		}
		padding: 60rpx;
	}

	.daohang {
		box-sizing: border-box;
		padding: 20rpx;
		display: flex;
		justify-content: space-around;

		image {
			width: 50rpx;
			height: 50rpx;
		}
	}

	.biaodan {
		background-color: white;
		display: flex;
		border-radius: 1rem;
	}

	.zong {
		background-color: #d6d6d6;
	}
</style>
