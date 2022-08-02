<template>
	<!--标签云-->
	<div class="ui segments m-box">
		<div class="ui secondary segment"><i class="tags icon"></i>标签云</div>
		<!-- <div class="ui yellow segment m-padding-small">
			<router-link :to="`/tag/${tag.name}`" class="ui label m-text-500" :class="tag.color" v-for="(tag,index) in tagList" :key="index">
				{{ tag.name }}
			</router-link>
		</div> -->
		<div data-v-55582d36="" class="ui yellow segment m-padding-small"><a data-v-55582d36="" href="/tag/密码学"
				class="ui label m-text-500 brown"> 密码学 </a><a data-v-55582d36="" href="/tag/RabbitMQ"
				class="ui label m-text-500 orange"> RabbitMQ </a><a data-v-55582d36="" href="/tag/消息队列"
				class="ui label m-text-500 blue"> 消息队列 </a><a data-v-55582d36="" href="/tag/布隆过滤器"
				class="ui label m-text-500 purple"> 布隆过滤器 </a><a data-v-55582d36="" href="/tag/定时任务"
				class="ui label m-text-500 blue"> 定时任务 </a><a data-v-55582d36="" href="/tag/Redis"
				class="ui label m-text-500 red"> Redis </a><a data-v-55582d36="" href="/tag/Spring Boot"
				class="ui label m-text-500 blue"> Spring Boot </a><a data-v-55582d36="" href="/tag/算法"
				class="ui label m-text-500 black"> 算法 </a><a data-v-55582d36="" href="/tag/数据结构"
				class="ui label m-text-500 black"> 数据结构 </a><a data-v-55582d36="" href="/tag/Sublime Text 3"
				class="ui label m-text-500 orange"> Sublime Text 3 </a><a data-v-55582d36="" href="/tag/Java"
				class="ui label m-text-500 red"> Java </a><a data-v-55582d36="" href="/tag/Python 3"
				class="ui label m-text-500 green"> Python 3 </a><a data-v-55582d36="" href="/tag/Vue Router"
				class="ui label m-text-500 green"> Vue Router </a><a data-v-55582d36="" href="/tag/Vue"
				class="ui label m-text-500 green"> Vue </a><a data-v-55582d36="" href="/tag/心情随写"
				class="ui label m-text-500 violet"> 心情随写 </a><a data-v-55582d36="" href="/tag/DFS"
				class="ui label m-text-500 orange"> DFS </a><a data-v-55582d36="" href="/tag/BFS"
				class="ui label m-text-500 red"> BFS </a><a data-v-55582d36="" href="/tag/图像识别"
				class="ui label m-text-500 teal"> 图像识别 </a><a data-v-55582d36="" href="/tag/连连看"
				class="ui label m-text-500 yellow"> 连连看 </a><a data-v-55582d36="" href="/tag/Typora"
				class="ui label m-text-500 green"> Typora </a><a data-v-55582d36="" href="/tag/PicGo"
				class="ui label m-text-500 black"> PicGo </a><a data-v-55582d36="" href="/tag/GitHub"
				class="ui label m-text-500 grey"> GitHub </a><a data-v-55582d36="" href="/tag/jsDelivr"
				class="ui label m-text-500 brown"> jsDelivr </a><a data-v-55582d36="" href="/tag/Swing"
				class="ui label m-text-500 pink"> Swing </a><a data-v-55582d36="" href="/tag/五子棋"
				class="ui label m-text-500 black"> 五子棋 </a><a data-v-55582d36="" href="/tag/Python-Flask"
				class="ui label m-text-500 olive"> Python-Flask </a><a data-v-55582d36="" href="/tag/Nginx"
				class="ui label m-text-500 pink"> Nginx </a><a data-v-55582d36="" href="/tag/归并排序"
				class="ui label m-text-500 purple"> 归并排序 </a><a data-v-55582d36="" href="/tag/败者树"
				class="ui label m-text-500 olive"> 败者树 </a><a data-v-55582d36="" href="/tag/外部排序"
				class="ui label m-text-500 blue"> 外部排序 </a><a data-v-55582d36="" href="/tag/跳表SkipList"
				class="ui label m-text-500 red"> 跳表SkipList </a><a data-v-55582d36="" href="/tag/KMP算法"
				class="ui label m-text-500 black"> KMP算法 </a><a data-v-55582d36="" href="/tag/字符串"
				class="ui label m-text-500 brown"> 字符串 </a></div>
	</div>
</template>

<script>
export default {
	// name: "Tags",
	// props: {
	// 	tagList: {
	// 		type: Array,
	// 		required: true
	// 	},
	// },
}
</script>

<style scoped>
.secondary.segment {
	padding: 10px;
}

.m-padding-small {
	padding: 7px;
}

.label {
	margin: 3px !important;
}
</style>