<template>
		<view class="">
			点击事件
		</view>
</template>

<script>
	export default {
		props:['keys'],
		data() {
			return {
				
			}
		},
		methods: {
			
		},
		created(){
		
		},
		mounted() {
			console.log(this.keys)
		}
	}
</script>

<style>

</style>
