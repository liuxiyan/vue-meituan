<template>
	<div class="nav">
		<router-link to="/goods" class="nav-item">点餐</router-link>
		<router-link to="/ratings" class="nav-item">评价</router-link>
		<router-link to="/seller" class="nav-item">商家</router-link>
	</div>
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

<style scoped>
.nav{
	display: flex;
	width: 100%;
	height: 40px;
	line-height: 40px;
	border-bottom: 1px solid #e4e4e4;
}	
.nav-item{
	flex: 1;
	text-align: center;
	font-size: 14px;
	text-decoration: none;
	color: #666;
	position: relative;
}

.nav .active:before{
	content:'';
	display: inline-block;
	width: 20px;
	height: 2px;
	background: #fb2;
	position: absolute;
	left: 50%;
	bottom: 0;
	margin-left: -10px;
}
</style>