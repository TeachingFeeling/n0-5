<template>
	<div>
		<div class="ui top attached segment" style="text-align: center">
			<h2 class="m-text-500">文章归档</h2>
			<p>好! 目前共计 {{ count }} 篇日志。 继续努力。</p>
		</div>
		<!-- <div class="ui attached segment">
			<div class="timeline">
				<div :class="colorObj[index%5]" v-for="(value,key,index) in blogMap" :key="index">
					<div class="tl-header">
						<a class="ui large label m-text-500">{{ key }}</a>
					</div>
					<div class="tl-item" v-for="blog in value" :key="blog.id">
						<div class="tl-wrap">
							<span class="tl-date">{{ blog.day }}</span>
							<a href="javascript:;" @click.prevent="toBlog(blog)">
								<div class="ui left pointing label tl-title">{{ blog.title }}</div>
							</a>
						</div>
					</div>
				</div>

				<div class="tl-header">
					<a class="ui black large label m-text-500">Hello World!</a>
				</div>
			</div>
		</div> -->
		<div data-v-c449438a="" class="ui attached segment">
			<div data-v-c449438a="" class="timeline">
				<div data-v-c449438a="" class="tl-blue">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2022年02月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">26日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">关于我从俄乌局势联想到密码学这档事</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-dark">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2021年12月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">31日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">2021 年度总结</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">19日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">LeetCode 每日一题</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">11日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">用 Log4j 花式启动计算器</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-green">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2021年10月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">23日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">RabbitMQ学习笔记</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-purple">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2021年04月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">04日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">v-if 之 diff 算法踩坑</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-red">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2021年03月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">31日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">短链接服务</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-blue">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2021年02月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">05日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Redis+定时任务实现访客标识及统计PV、UV
								</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-dark">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2020年12月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">31日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">2020 年度总结</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-green">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2020年08月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">23日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Vue 锚点定位导致页面刷新的解决办法
								</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">06日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">又是一次LOL对局中被踢出...</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-purple">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2020年07月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">15日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Vue电商后台管理系统</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-red">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2020年06月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">03日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">
									Python调用腾讯API取屏幕内容翻译并语音输出</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-blue">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2020年05月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">21日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">连连看自动玩</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">06日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">使用 GitHub + jsDelivr +
									PicGo + Typora 搭建图床</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">05日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">【旧版】博客系统开发总结</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-dark">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2019年12月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">19日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">记Java三级项目――五子棋</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-green">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2019年11月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">22日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">
									使用Ubuntu+Nginx+Flask将Python3应用部署到服务器</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-purple">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2019年10月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">25日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Python3 基础学习笔记
									04——文本词频统计</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">25日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Python3 基础学习笔记
									03——组合数据类型</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">24日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Python3 基础学习笔记
									02——库、异常、循环</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">24日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Python3 基础学习笔记
									01——数据类型及字符串</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">20日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">Sublime Text
									3定义自己的Command</div>
							</a></div>
					</div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">17日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">外部排序&amp;败者树&amp;多路归并
								</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-red">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2019年09月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">15日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">跳跃列表SkipList</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-blue">
					<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
							class="ui large label m-text-500">2019年07月</a></div>
					<div data-v-c449438a="" class="tl-item">
						<div data-v-c449438a="" class="tl-wrap"><span data-v-c449438a="" class="tl-date">13日</span><a
								data-v-c449438a="" href="javascript:;">
								<div data-v-c449438a="" class="ui left pointing label tl-title">字符串匹配——KMP算法</div>
							</a></div>
					</div>
				</div>
				<div data-v-c449438a="" class="tl-header"><a data-v-c449438a=""
						class="ui black large label m-text-500">Hello World!</a></div>
			</div>
		</div>
	</div>
</template>

<script>
// import {getArchives} from "@/api/archives";

export default {
	name: "Archives",
	data() {
		return {
			// blogMap: {},
			// count: 0,
			// colorObj: {
			// 	0: 'tl-blue',
			// 	1: 'tl-dark',
			// 	2: 'tl-green',
			// 	3: 'tl-purple',
			// 	4: 'tl-red',
			// }
		}
	},
	created() {
		// this.getArchives()
	},
	methods: {
		// getArchives() {
		// 	getArchives().then(res => {
		// 		if (res.code === 200) {
		// 			this.blogMap = res.data.blogMap
		// 			this.count = res.data.count
		// 		} else {
		// 			this.msgError(res.msg);
		// 		}
		// 	}).catch(() => {
		// 		this.msgError("请求失败");
		// 	})
		// },
		// toBlog(blog) {
		// 	this.$store.dispatch('goBlogPage', blog)
		// }
	}
}
</script>

<style scoped>
.timeline {
	margin: 20px 0;
}

.tl-header {
	width: 12em;
	text-align: center;
}

.tl-date {
	position: relative;
	top: 10px;
	display: block;
	float: left;
	width: 4.5em;
	margin-left: -7.5em;
	text-align: right;
}

.tl-wrap {
	padding: 15px 0 15px 20px;
	margin-left: 6em;
	border-style: solid;
	border-width: 0 0 0 4px;
}

.tl-wrap:before {
	position: relative;
	top: 15px;
	float: left;
	width: 10px;
	height: 10px;
	margin-left: -27px;
	background: #fff;
	border-color: inherit;
	border-style: solid;
	border-width: 3px;
	border-radius: 50%;
	content: "";
	box-shadow: 0 0 0 4px #fff;
}

.tl-wrap:hover:before {
	background: 0 0;
	border-color: #fff;
}

.tl-title {
	margin-left: 0 !important;
	letter-spacing: 0.3px !important;
	font-size: 14px !important;
	font-weight: 500 !important;
	padding: 12px 15px !important;
}

.tl-blue .tl-header a,
.tl-blue .tl-item .tl-title {
	background: #23b7e5 !important;
	color: #fff !important;
}

.tl-blue .tl-item .tl-wrap {
	border-color: #23b7e5;
}

.tl-dark .tl-header a,
.tl-dark .tl-item .tl-title {
	background: #3a3f51 !important;
	color: #fff !important;
}

.tl-dark .tl-item .tl-wrap {
	border-color: #3a3f51;
}

.tl-green .tl-header a,
.tl-green .tl-item .tl-title {
	background: #27c24c !important;
	color: #fff !important;
}

.tl-green .tl-item .tl-wrap {
	border-color: #27c24c;
}

.tl-purple .tl-header a,
.tl-purple .tl-item .tl-title {
	background: #7266ba !important;
	color: #fff !important;
}

.tl-purple .tl-item .tl-wrap {
	border-color: #7266ba;
}

.tl-red .tl-header a,
.tl-red .tl-item .tl-title {
	background: #f05050 !important;
	color: #fff !important;
}

.tl-red .tl-item .tl-wrap {
	border-color: #f05050;
}
</style>