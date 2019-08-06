<template>
	<view class="home">
		<view class="home-header">
			<image src="" mode=""></image>
			<view class="home-header-name">
				<view class="home-header-name-1">
					昵称：23333
				</view>
				<view class="home-header-name-2"></view>
			</view>
		</view>
		<view class="home-content"></view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="less" scoped>
	.home{
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background-color: red;
		display: flex;
		flex-direction: column;
		&-header{
			padding-top: 50upx;
			padding-bottom: 50upx;
			background-color: aquamarine;
			display: flex;
			image{
				width: 150upx;
				height: 150upx;
				border-radius: 50%;
				border: 1upx solid #ccc;
				margin-left: 100upx;
			}
			&-name{
				flex: 1;
				margin-left: 30upx;
				background-color: orange;
				&-1{
					
				}
				&-2{
					
				}
			}
		}
		&-content{
			
		}
	}
</style>
