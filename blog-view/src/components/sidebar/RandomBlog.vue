<template>
	<!--随机文章-->
	<div class="ui segments m-box">
		<div class="ui secondary segment"><i class="bookmark icon"></i>随机文章</div>
		<div class="ui yellow segment">
			<div class="ui divided items">
				<!-- <div class="m-item" v-for="blog in randomBlogList" :key="blog.id" @click.prevent="toBlog(blog)">
					<div class="img" :style="{'background-image':'url(' + blog.firstPicture + ')'}"></div>
					<div class="info">
						<div class="date">{{ blog.createTime | dateFormat('YYYY-MM-DD') }}</div>
						<div class="title">{{ blog.title }}</div>
						
						
					</div>
					
				</div> -->
				<div data-v-10ce263a="" class="ui yellow segment">
					<div data-v-10ce263a="" class="ui divided items">
						<div data-v-10ce263a="" class="m-item">
							<div data-v-10ce263a="" class="img"
								style="background-image: url(&quot;https://cdn.naccl.top/blog/blogHosting/2021/12/B02/LeetCode.png&quot;);">
							</div>
							<div data-v-10ce263a="" class="info">
								<div data-v-10ce263a="" class="date">2021-12-19</div>
								<div data-v-10ce263a="" class="title">LeetCode 每日一题</div>
							</div>
						</div>
						<div data-v-10ce263a="" class="m-item">
							<div data-v-10ce263a="" class="img"
								style="background-image: url(&quot;https://cdn.naccl.top/blog/blogHosting/2020/08/B02/first.jpg&quot;);">
							</div>
							<div data-v-10ce263a="" class="info">
								<div data-v-10ce263a="" class="date">2020-08-23</div>
								<div data-v-10ce263a="" class="title">Vue 锚点定位导致页面刷新的解决办法</div>
							</div>
						</div>
						<div data-v-10ce263a="" class="m-item">
							<div data-v-10ce263a="" class="img"
								style="background-image: url(&quot;https://cdn.naccl.top/blog/blogHosting/2021/02/B01/003.png&quot;);">
							</div>
							<div data-v-10ce263a="" class="info">
								<div data-v-10ce263a="" class="date">2021-02-05</div>
								<div data-v-10ce263a="" class="title">Redis+定时任务实现访客标识及统计PV、UV</div>
							</div>
						</div>
						<div data-v-10ce263a="" class="m-item">
							<div data-v-10ce263a="" class="img"
								style="background-image: url(&quot;https://cdn.naccl.top/blog/blogHosting/2021/03/B01/001.png&quot;);">
							</div>
							<div data-v-10ce263a="" class="info">
								<div data-v-10ce263a="" class="date">2021-03-31</div>
								<div data-v-10ce263a="" class="title">短链接服务</div>
							</div>
						</div>
						<div data-v-10ce263a="" class="m-item">
							<div data-v-10ce263a="" class="img"
								style="background-image: url(&quot;https://cdn.naccl.top/blog/blogHosting/2019/10/B01/001.png&quot;);">
							</div>
							<div data-v-10ce263a="" class="info">
								<div data-v-10ce263a="" class="date">2019-07-13</div>
								<div data-v-10ce263a="" class="title">字符串匹配——KMP算法</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	// name: "RandomBlog",
	// props: {
	// 	randomBlogList: {
	// 		type: Array,
	// 		required: true
	// 	},
	// },
	// methods: {
	// 	toBlog(blog) {
	// 		this.$store.dispatch('goBlogPage', blog)
	// 	}
	// }
}
</script>

<style scoped>
.secondary.segment {
	padding: 10px;
}

.ui.divided.items .m-item:first-child {
	margin-top: 0;
}

.ui.divided.items .m-item {
	margin-top: 1rem;
	height: 7rem;
	position: relative;
	overflow: hidden;
	border-radius: 5px;
	cursor: pointer;
	user-select: none;
}

.ui.divided.items .m-item .img {
	position: absolute;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	object-fit: cover;
	background-position-x: center;
	background-position-y: center;
	background-size: cover;
}

.ui.divided.items .m-item .info {
	z-index: 1;
	background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.8));
	position: absolute;
	left: 0;
	right: 0;
	bottom: 0;
	padding: .5rem !important;
	font-size: 12px;
	color: white;
}

.ui.divided.items .m-item .info .title {
	overflow: hidden;
	text-overflow: ellipsis;
	display: -webkit-box;
	-webkit-box-orient: vertical;
	-webkit-line-clamp: 1;
	word-break: break-word;
}
</style>