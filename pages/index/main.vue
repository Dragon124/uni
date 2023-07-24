<template>
	<view>
		<view class="head">
			标题
		</view>
		<view class="list-scroll-view">
			<view class="course-card" v-for="(item) in 3">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>uniapp布局</view>
				<view>免费</view>
			</view>
		</view>
		<view class="tools">
			<view class="tools-item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>首页</view>
			</view>
			<view class="tools-item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>分类</view>
			</view>
			<view class="tools-item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>课表</view>
			</view>
			<view class="tools-item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>我的</view>
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

<style>
	.head {
		text-align: center;
	}

	.list-scroll-view {
		flex-wrap: wrap;
		display: flex;
		flex-direction: row;
		margin-left: 2vw;
		margin-right: 2vw;
		justify-content: space-between;
	}

	.course-card {
		width: 47vw;
	}

	.course-card image {
		width: 100%;
	}

	.tools {
		justify-content: space-between;
		display: flex;
	}
</style>