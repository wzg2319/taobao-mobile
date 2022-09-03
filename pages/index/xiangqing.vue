<template>
	<view>
		<view class="daohang">
			<view class="fanhui">
				<image src="../../static/heifanhui.png" mode=""></image>
				<p>|</p>
				<image src="../../static/heigengduo.png" mode=""></image>
			</view>
		<view class="shuru">
			<p>商品</p>
				<input class="uni-input" confirm-type="search" />
		<image src="../../static/guanbi.png" mode=""></image>
		<view class="sou">
			搜索
		</view>
		</view>
		</view>
		<view class="xuanxiangall">
			<view class="xuanxiangzuo">
					<P>综合</P>
					<p>销量</p><p>品牌</p>
				</view>
				<view class="xuanxiangyou">
					<image src="../../static/fangkuai.png" mode=""></image>
					<p>|</p>
					<p>筛选</p>
			<image src="../../static/shaixuan.png" mode=""></image>	
				</view>
		</view>
<view class="liulan">
	<view class="liulanzuo">
	<image src="../../static/logo.png" mode=""></image>
		<p>xxx  xxx  xxx</p>
		<p>aaa|aaa|aaa</p>
		<p>howmuch</p>
		<p>进店</p>
	</view>
	<view class="liulanyou">
	<image src="../../static/logo.png" mode=""></image>
		<p>xxx  xxx  xxx</p>
		<p>aaa|aaa|aaa</p>
		<p>howmuch</p>
		<p>进店</p>
	</view>
</view>
<view class="liulan">
	<view class="liulanzuo">
	<image src="../../static/logo.png" mode=""></image>
		<p>xxx  xxx  xxx</p>
		<p>aaa|aaa|aaa</p>
		<p>howmuch</p>
		<p>进店</p>
	</view>
	<view class="liulanyou">
	<image src="../../static/logo.png" mode=""></image>
		<p>xxx  xxx  xxx</p>
		<p>aaa|aaa|aaa</p>
		<p>howmuch</p>
		<p>进店</p>
	</view>
</view>
<view class="liulan">
	<view class="liulanzuo">
	<image src="../../static/logo.png" mode=""></image>
		<p>xxx  xxx  xxx</p>
		<p>aaa|aaa|aaa</p>
		<p>howmuch</p>
		<p>进店</p>
	</view>
	<view class="liulanyou">
	<image src="../../static/logo.png" mode=""></image>
		<p>xxx  xxx  xxx</p>
		<p>aaa|aaa|aaa</p>
		<p>howmuch</p>
		<p>进店</p>
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
	.liulan{
		display: flex;
		justify-content: space-around;
		margin-top: 20rpx;
		image{width: 300rpx;
		height: 300rpx;}
	}
	.xuanxiangzuo{
		p{padding-right: 110rpx;
			width: 70rpx;}
		display:flex;}
.xuanxiangyou{
	width: 650rpx;
	display: flex;
	justify-content: end;
	image{
		padding-right: 20rpx;
	width: 40rpx;
	height: 40rpx;
}}
	.xuanxiangall{
		margin-top: 20rpx;
		width: 100rvw;
		display: flex;
	}
.shuru{display: flex;
	align-items: center;
	margin:20rpx;
	border:solid 1px red;
	background-color: #f7f7f7;
	border-radius: 1rem;
	image{
		width: 50rpx;
		height: 50rpx;
	}
	p{padding-left: 20rpx;
	width: 70rpx;}
	}
	.uni-input{width: 250rpx;
	height: 70rpx;}
	.sou{
		display: flex;
		justify-content: center;
		align-items: center;
		width: 120rpx;
		height: 70rpx;
		color: white;
		border-radius: 1rem;


		    background-image: linear-gradient(-15deg,#ff5000,#ff6900 61%,#ff963f);
	}
	.daohang{
		display: flex;
		align-items: center;
	}
	.fanhui{
		width:170rpx;
		height: 70rpx;
		border: 1px solid black;
	 border-radius: 1rem;
		margin:20rpx;
		display: flex;
		align-items: center;
		image{
		width: 45rpx;
		height: 45rpx;
		margin-left: 20rpx;
		margin-right: 20rpx;
	}}
</style>
