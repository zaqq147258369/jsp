<template>
	<view class="contenting">
		<!-- 搜索 -->
		<Search></Search>
		<Swipers></Swipers>
		<Purchase></Purchase>
		<List></List>
		<Commodity></Commodity>
	</view>
</template>

<script>
	import Search from './components/search.vue'
	import Swipers from './components/swiper.vue'
	import Purchase from './components/purchase.vue'
	import List from './components/list.vue'
	import Commodity from './components/commodity.vue'
	
	export default {
		components:{
			Search,
			Swipers,
			Purchase,
			List,
			Commodity,
		},
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

<style scoped="scoped">
	.contenting{
		margin: 0 15rpx;
	}
</style>
