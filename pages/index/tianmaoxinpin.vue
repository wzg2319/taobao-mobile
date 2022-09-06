<template>
	<view>
		<view class="heihedaohang">
			
	
		<view class="heihedaohang1">
<view class="heihezuo">
	<image src="../../static/fanhui.png" mode="" style="width: 50rpx; height: 50rpx;"></image>
	<image src="../../static/xiaoheihe.webp" mode=" " style="width: 250rpx; height: 50rpx;"></image>
</view>		
	<view class="heiheyou">
		<image src="../../static/fenxiang.webp" mode="" style="width: 40rpx; margin-left: 320rpx;
		height: 40rpx;"></image>
	</view>
	</view>
	<view class="heihexia">
		<image src="../../static/xinpin.png" mode="" style="width: 100vw; height: 100rpx;" ></image>
	<image src="../../static/kaiheyouli.webp" mode="" style="width: 100vw; height: 100rpx;"></image>
	</view>
	</view>
	<view class="ggq">
		<view class="guanggaoshang">
			<p>新品一元抽</p>
			<view class="yiyuanchou">
				<view class="ggst">
					<image src="../../static/logo.png" mode="" style="height: 80rpx;width: 80rpx;"></image>
					<p>9999参与</p>
				</view>
				<view class="ggst">
					<image src="../../static/logo.png" mode=""style="height: 80rpx;width: 80rpx;" ></image>
					<p>9999参与</p>
				</view>
			</view>
			
		</view>
		<view class="guanggaoshang">
			<p>新品一元抽</p>
			<view class="yiyuanchou">
				<view class="ggst">
					<image src="../../static/logo.png" mode="" style="height: 80rpx;width: 80rpx;"></image>
					<p>9999参与</p>
				</view>
				<view class="ggst">
					<image src="../../static/logo.png" mode=""style="height: 80rpx;width: 80rpx;" ></image>
					<p>9999参与</p>
				</view>
			</view>
			
	</view>
	
	</view>
	<view class="wodepinpai">
		<p>我的品牌</p>
		<view class="pinpaihb">
			<image src="../../static/logo.png" mode=""></image>
			<image src="../../static/logo.png" mode=""></image>
			<image src="../../static/logo.png" mode=""></image>

		</view>
	</view>
	<view class="xinpin">
		<view class="wenzi">
			<p>热度新品</p><p>新口味</p><p>新联名</p><p>新面料</p><p>新工效</p>
		</view>
	<view class="xinpintu">
		<image src="../../static/logo.png" mode=""></image>
		<image src="../../static/logo.png" mode=""></image>
	</view>
	</view>
<view class="hhdb">
	<p>小黑盒</p>
	<p>抽签</p>
	<p>发布</p>
	<p>新料</p>
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
	.hhdb{
		display: flex;
		justify-content: space-around;
	}
	.xinpintu{
		display: flex;
		justify-content: space-around;
		margin: 20rpx;
		image{width: 300rpx;
	height: 300rpx;}}
	.wenzi{display: flex;justify-content: space-around;
		
	}
	.pinpaihb{image{margin: 20rpx;
		width: 200rpx;
		height: 200rpx;}
		}

	.ggq{display: flex;

	justify-content: space-around;}
	.guanggaoshang{
		padding-top: 180rpx;
		margin-left: 20rpx;
	}
	.yiyuanchou{
		display: flex;
	}
	.heihexia{
		margin-top: 300rpx;
	}
	.heihedaohang{background-image: url("@/static/heihebeijing.png");
	width: 100%;
	height: 450rpx;}
.heihedaohang1{
	padding: 20rpx;
	display: flex;
	align-items: center;
	width: 100%;
background-image: url("@/static/heihebeijing.png");
}
</style>
