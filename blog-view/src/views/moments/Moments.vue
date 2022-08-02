<template>
	<div>
		<div class="ui top attached segment" style="text-align: center">
			<h2 class="m-text-500">我的动态</h2>
		</div>
		<!-- <div class="ui attached segment m-padding-bottom-large">
			<div class="moments">
				<div class="moment" v-for="(moment,index) in momentList" :key="index">
					<div class="avatar">
						<img :src="$store.state.introduction.avatar">
					</div>
					<div class="ui card">
						<div class="content m-top">
							<span style="font-weight: 700">{{ $store.state.introduction.name }}</span>
							<span class="right floated">{{ moment.createTime | dateFromNow }}</span>
						</div>
						<div class="content typo" :class="{'privacy':!moment.published}" v-viewer v-html="moment.content"></div>
						<div class="extra content">
							<a class="left floated" @click="like(moment.id)">
								<i class="heart icon" :class="isLike(moment.id)?'like-color':'outline'"></i>{{ moment.likes }}
							</a>
						</div>
					</div>
					
				</div>
			</div>

			<el-pagination @current-change="handleCurrentChange" :current-page="pageNum" :page-count="totalPage"
			               layout="prev, pager, next" background hide-on-single-page class="pagination">
			</el-pagination>
		</div> -->
		<div data-v-75aebb7f="" class="ui attached segment m-padding-bottom-large">
			<div data-v-75aebb7f="" class="moments">
				<div data-v-75aebb7f="" class="moment">
					<div data-v-75aebb7f="" class="avatar"><img data-v-75aebb7f="" src="/img/avatar.jpg"></div>
					<div data-v-75aebb7f="" class="ui card">
						<div data-v-75aebb7f="" class="content m-top"><span data-v-75aebb7f=""
								style="font-weight: 700;">Naccl</span><span data-v-75aebb7f=""
								class="right floated">2022-05-18 22:49</span></div>
						<div data-v-75aebb7f="" class="content typo">
							<p>国内网络环境真是令人反胃，cdn.jsdelivr.net也被墙了，啥时候干脆把出国海底光缆都物理切断得了，晦气</p>
						</div>
						<div data-v-75aebb7f="" class="extra content"><a data-v-75aebb7f="" class="left floated"><i
									data-v-75aebb7f="" class="heart icon outline"></i>24 </a></div>
					</div>
				</div>
				<div data-v-75aebb7f="" class="moment">
					<div data-v-75aebb7f="" class="avatar"><img data-v-75aebb7f="" src="/img/avatar.jpg"></div>
					<div data-v-75aebb7f="" class="ui card">
						<div data-v-75aebb7f="" class="content m-top"><span data-v-75aebb7f=""
								style="font-weight: 700;">Naccl</span><span data-v-75aebb7f=""
								class="right floated">2022-03-01 00:55</span></div>
						<div data-v-75aebb7f="" class="content typo">
							<p>俺也不晓得最近是咋了，博客的pv上千了，看来不能自娱自乐了呢🥲</p>
						</div>
						<div data-v-75aebb7f="" class="extra content"><a data-v-75aebb7f="" class="left floated"><i
									data-v-75aebb7f="" class="heart icon outline"></i>66 </a></div>
					</div>
				</div>
				<div data-v-75aebb7f="" class="moment">
					<div data-v-75aebb7f="" class="avatar"><img data-v-75aebb7f="" src="/img/avatar.jpg"></div>
					<div data-v-75aebb7f="" class="ui card">
						<div data-v-75aebb7f="" class="content m-top"><span data-v-75aebb7f=""
								style="font-weight: 700;">Naccl</span><span data-v-75aebb7f=""
								class="right floated">2021-12-20 19:49</span></div>
						<div data-v-75aebb7f="" class="content typo">
							<p>今天最热闹的事估计就是 <a href="https://github.com/jsdelivr/jsdelivr/issues/18348" target="_blank"
									rel="external nofollow noopener">jsDelivr 在中国的 CDN 服务裂了</a>，众多博客都成了纯文本，简直是三年一遇</p>
							<p>由于本博客连 Vue 的 js 文件都是用的 cdn，所以如果当时你访问了，甚至连一个字都看不到</p>
							<p>官方最后的解决办法还是暂时把国内的域名解析切换到了 Fastly CDN，<a
									href="https://github.com/jsdelivr/jsdelivr/issues/18348#issuecomment-997777996"
									target="_blank" rel="external nofollow noopener">官方回复</a>也是匪夷所思</p>
							<p>有趣的是，因为 bootcdn 主页也用了 jsDelivr 的 cdn，导致它自己的页面样式也乱了，太魔幻了</p>
							<p><img src="https://cdn.naccl.top/blog/blogHosting/moment/20211220.png" alt="20211220.png">
							</p>
							<p>考虑是否需要加上 <a href="https://github.com/EtherDream/freecdn" target="_blank"
									rel="external nofollow noopener">freecdn</a> 😋</p>
						</div>
						<div data-v-75aebb7f="" class="extra content"><a data-v-75aebb7f="" class="left floated"><i
									data-v-75aebb7f="" class="heart icon outline"></i>26 </a></div>
					</div>
				</div>
				<div data-v-75aebb7f="" class="moment">
					<div data-v-75aebb7f="" class="avatar"><img data-v-75aebb7f="" src="/img/avatar.jpg"></div>
					<div data-v-75aebb7f="" class="ui card">
						<div data-v-75aebb7f="" class="content m-top"><span data-v-75aebb7f=""
								style="font-weight: 700;">Naccl</span><span data-v-75aebb7f=""
								class="right floated">2021-09-16 13:22</span></div>
						<div data-v-75aebb7f="" class="content typo">
							<p>原服务器到期了，打了两天前的服务器镜像（丢了两天数据），迁移成功</p>
						</div>
						<div data-v-75aebb7f="" class="extra content"><a data-v-75aebb7f="" class="left floated"><i
									data-v-75aebb7f="" class="heart icon outline"></i>35 </a></div>
					</div>
				</div>
				<div data-v-75aebb7f="" class="moment">
					<div data-v-75aebb7f="" class="avatar"><img data-v-75aebb7f="" src="/img/avatar.jpg"></div>
					<div data-v-75aebb7f="" class="ui card">
						<div data-v-75aebb7f="" class="content m-top"><span data-v-75aebb7f=""
								style="font-weight: 700;">Naccl</span><span data-v-75aebb7f=""
								class="right floated">2021-06-14 15:00</span></div>
						<div data-v-75aebb7f="" class="content typo">
							<p>
								<meting-js server="netease" type="song" id="479598964" theme="#25CCF7">
									<div class="aplayer aplayer-withlrc">
										<div class="aplayer-body">
											<div class="aplayer-pic"
												style="background-image: url(&quot;https://api.i-meto.com/meting/api?server=netease&amp;type=pic&amp;id=109951162931819035&amp;auth=b8f6e2e8e1b92444d697c19be61e1d50672995bd&quot;); background-color: rgb(37, 204, 247);">
												<div class="aplayer-button aplayer-play"><svg
														xmlns="http://www.w3.org/2000/svg" version="1.1"
														viewBox="0 0 16 31">
														<path
															d="M15.552 15.168q0.448 0.32 0.448 0.832 0 0.448-0.448 0.768l-13.696 8.512q-0.768 0.512-1.312 0.192t-0.544-1.28v-16.448q0-0.96 0.544-1.28t1.312 0.192z">
														</path>
													</svg></div>
											</div>
											<div class="aplayer-info">
												<div class="aplayer-music">
													<span class="aplayer-title">椿</span>
													<span class="aplayer-author"> - 沈以诚</span>
												</div>
												<div class="aplayer-lrc">
													<div class="aplayer-lrc-contents"
														style="transform: translateY(0); -webkit-transform: translateY(0);">
														<p class="aplayer-lrc-current">作词 : 沈以诚</p>

														<p>作曲 : 沈以诚</p>

														<p>恍惚间 浸透了回忆</p>

														<p>漫漫的回忆 存在的回忆</p>

														<p>只看见 遗忘的笑脸</p>

														<p>纯洁的笑脸不在身边</p>

														<p>想实现 从前的诺言</p>

														<p>不轻的诺言 和你的诺言</p>

														<p>却描绘 无期限的诗</p>

														<p>由寓意的诗刻画的线</p>

														<p>乔木落叶 告诉我时间变迁</p>

														<p>你仍旧倚靠石头看岁岁年年</p>

														<p>惊觉两鬓霜白长叹一声哀怨</p>

														<p>也不过匆匆弹指间</p>

														<p>不在意我存在你心里面</p>

														<p>只记得当时没有那么远</p>

														<p>一眼朝如青丝暮成雪</p>

														<p>美梦惊你不在眼前</p>

														<p>我想给你一颗我的眼</p>

														<p>倒映着曾拾起的缘</p>

														<p>若皆是一场镜花水月</p>

														<p>也不想忘记你的颜</p>

														<p>唯一心愿</p>

														<p>恍惚间 浸透了回忆</p>

														<p>漫漫的回忆 存在的回忆</p>

														<p>只看见 遗忘的笑脸</p>

														<p>纯洁的笑脸不在身边</p>

														<p>想实现 从前的诺言</p>

														<p>不轻的诺言 和你的诺言</p>

														<p>却描绘 无期限的诗</p>

														<p>由寓意的诗刻画的线</p>

														<p>乔木落叶 告诉我时间变迁</p>

														<p>你仍旧倚靠石头看岁岁年年</p>

														<p>惊觉两鬓霜白长叹一声哀怨</p>

														<p>也不过匆匆弹指间</p>

														<p>不在意我存在你心里面</p>

														<p>只记得当时没有那么远</p>

														<p>一眼朝如青丝暮成雪</p>

														<p>美梦惊你不在眼前</p>

														<p>我想给你一颗我的眼</p>

														<p>倒映着曾拾起的缘</p>

														<p>若皆是一场镜花水月</p>

														<p>也不想忘记你的颜</p>

														<p>唯一心愿</p>
													</div>
												</div>
												<div class="aplayer-controller">
													<div class="aplayer-bar-wrap">
														<div class="aplayer-bar">
															<div class="aplayer-loaded" style="width: 3.7566%;"></div>
															<div class="aplayer-played"
																style="width: 0; background: #25CCF7;">
																<span class="aplayer-thumb"
																	style="background: #25CCF7;">
																	<span class="aplayer-loading-icon"><svg
																			xmlns="http://www.w3.org/2000/svg"
																			version="1.1" viewBox="0 0 32 32">
																			<path
																				d="M4 16c0-6.6 5.4-12 12-12s12 5.4 12 12c0 1.2-0.8 2-2 2s-2-0.8-2-2c0-4.4-3.6-8-8-8s-8 3.6-8 8 3.6 8 8 8c1.2 0 2 0.8 2 2s-0.8 2-2 2c-6.6 0-12-5.4-12-12z">
																			</path>
																		</svg></span>
																</span>
															</div>
														</div>
													</div>
													<div class="aplayer-time">
														<span class="aplayer-time-inner">
															<span class="aplayer-ptime">00:00</span> / <span
																class="aplayer-dtime">03:37</span>
														</span>
														<span class="aplayer-icon aplayer-icon-back">
															<svg xmlns="http://www.w3.org/2000/svg" version="1.1"
																viewBox="0 0 32 32">
																<path
																	d="M25.468 6.947c-0.326-0.172-0.724-0.151-1.030 0.057l-6.438 4.38v-3.553c0-0.371-0.205-0.71-0.532-0.884-0.326-0.172-0.724-0.151-1.030 0.057l-12 8.164c-0.274 0.186-0.438 0.496-0.438 0.827s0.164 0.641 0.438 0.827l12 8.168c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-3.556l6.438 4.382c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-16.333c0-0.371-0.205-0.71-0.532-0.884z">
																</path>
															</svg>
														</span>
														<span class="aplayer-icon aplayer-icon-play">
															<svg xmlns="http://www.w3.org/2000/svg" version="1.1"
																viewBox="0 0 16 31">
																<path
																	d="M15.552 15.168q0.448 0.32 0.448 0.832 0 0.448-0.448 0.768l-13.696 8.512q-0.768 0.512-1.312 0.192t-0.544-1.28v-16.448q0-0.96 0.544-1.28t1.312 0.192z">
																</path>
															</svg>
														</span>
														<span class="aplayer-icon aplayer-icon-forward">
															<svg xmlns="http://www.w3.org/2000/svg" version="1.1"
																viewBox="0 0 32 32">
																<path
																	d="M25.468 6.947c-0.326-0.172-0.724-0.151-1.030 0.057l-6.438 4.38v-3.553c0-0.371-0.205-0.71-0.532-0.884-0.326-0.172-0.724-0.151-1.030 0.057l-12 8.164c-0.274 0.186-0.438 0.496-0.438 0.827s0.164 0.641 0.438 0.827l12 8.168c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-3.556l6.438 4.382c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-16.333c0-0.371-0.205-0.71-0.532-0.884z">
																</path>
															</svg>
														</span>
														<div class="aplayer-volume-wrap">
															<button type="button"
																class="aplayer-icon aplayer-icon-volume-down"><svg
																	xmlns="http://www.w3.org/2000/svg" version="1.1"
																	viewBox="0 0 28 32">
																	<path
																		d="M13.728 6.272v19.456q0 0.448-0.352 0.8t-0.8 0.32-0.8-0.32l-5.952-5.952h-4.672q-0.48 0-0.8-0.352t-0.352-0.8v-6.848q0-0.48 0.352-0.8t0.8-0.352h4.672l5.952-5.952q0.32-0.32 0.8-0.32t0.8 0.32 0.352 0.8zM20.576 16q0 1.344-0.768 2.528t-2.016 1.664q-0.16 0.096-0.448 0.096-0.448 0-0.8-0.32t-0.32-0.832q0-0.384 0.192-0.64t0.544-0.448 0.608-0.384 0.512-0.64 0.192-1.024-0.192-1.024-0.512-0.64-0.608-0.384-0.544-0.448-0.192-0.64q0-0.48 0.32-0.832t0.8-0.32q0.288 0 0.448 0.096 1.248 0.48 2.016 1.664t0.768 2.528z">
																	</path>
																</svg></button>
															<div class="aplayer-volume-bar-wrap">
																<div class="aplayer-volume-bar">
																	<div class="aplayer-volume"
																		style="height: 70%; background: rgb(37, 204, 247) none repeat scroll 0% 0%;">
																	</div>
																</div>
															</div>
														</div>
														<button type="button" class="aplayer-icon aplayer-icon-order">
															<svg xmlns="http://www.w3.org/2000/svg" version="1.1"
																viewBox="0 0 32 32">
																<path
																	d="M0.622 18.334h19.54v7.55l11.052-9.412-11.052-9.413v7.549h-19.54v3.725z">
																</path>
															</svg>
														</button>
														<button type="button" class="aplayer-icon aplayer-icon-loop">
															<svg xmlns="http://www.w3.org/2000/svg" version="1.1"
																viewBox="0 0 29 32">
																<path
																	d="M9.333 9.333h13.333v4l5.333-5.333-5.333-5.333v4h-16v8h2.667v-5.333zM22.667 22.667h-13.333v-4l-5.333 5.333 5.333 5.333v-4h16v-8h-2.667v5.333z">
																</path>
															</svg>
														</button>
														<button type="button" class="aplayer-icon aplayer-icon-menu">
															<svg xmlns="http://www.w3.org/2000/svg" version="1.1"
																viewBox="0 0 22 32">
																<path
																	d="M20.8 14.4q0.704 0 1.152 0.48t0.448 1.12-0.48 1.12-1.12 0.48h-19.2q-0.64 0-1.12-0.48t-0.48-1.12 0.448-1.12 1.152-0.48h19.2zM1.6 11.2q-0.64 0-1.12-0.48t-0.48-1.12 0.448-1.12 1.152-0.48h19.2q0.704 0 1.152 0.48t0.448 1.12-0.48 1.12-1.12 0.48h-19.2zM20.8 20.8q0.704 0 1.152 0.48t0.448 1.12-0.48 1.12-1.12 0.48h-19.2q-0.64 0-1.12-0.48t-0.48-1.12 0.448-1.12 1.152-0.48h19.2z">
																</path>
															</svg>
														</button>
														<button type="button" class="aplayer-icon aplayer-icon-lrc">
															<svg xmlns="http://www.w3.org/2000/svg" version="1.1"
																viewBox="0 0 32 32">
																<path
																	d="M26.667 5.333h-21.333c-0 0-0.001 0-0.001 0-1.472 0-2.666 1.194-2.666 2.666 0 0 0 0.001 0 0.001v-0 16c0 0 0 0.001 0 0.001 0 1.472 1.194 2.666 2.666 2.666 0 0 0.001 0 0.001 0h21.333c0 0 0.001 0 0.001 0 1.472 0 2.666-1.194 2.666-2.666 0-0 0-0.001 0-0.001v0-16c0-0 0-0.001 0-0.001 0-1.472-1.194-2.666-2.666-2.666-0 0-0.001 0-0.001 0h0zM5.333 16h5.333v2.667h-5.333v-2.667zM18.667 24h-13.333v-2.667h13.333v2.667zM26.667 24h-5.333v-2.667h5.333v2.667zM26.667 18.667h-13.333v-2.667h13.333v2.667z">
																</path>
															</svg>
														</button>
													</div>
												</div>
											</div>
											<div class="aplayer-notice"></div>
											<div class="aplayer-miniswitcher"><button class="aplayer-icon"><svg
														xmlns="http://www.w3.org/2000/svg" version="1.1"
														viewBox="0 0 32 32">
														<path
															d="M22 16l-10.105-10.6-1.895 1.987 8.211 8.613-8.211 8.612 1.895 1.988 8.211-8.613z">
														</path>
													</svg></button></div>
										</div>
										<div class="aplayer-list" style="max-height: 250px">
											<ol style="max-height: 250px">

												<li class="aplayer-list-light">
													<span class="aplayer-list-cur"
														style="background-color: #25CCF7;"></span>
													<span class="aplayer-list-index">1</span>
													<span class="aplayer-list-title">椿</span>
													<span class="aplayer-list-author">沈以诚</span>
												</li>

											</ol>
										</div>
									</div>
								</meting-js>
							</p>
							<p>实习一个月，累并快乐着</p>
						</div>
						<div data-v-75aebb7f="" class="extra content"><a data-v-75aebb7f="" class="left floated"><i
									data-v-75aebb7f="" class="heart icon outline"></i>42 </a></div>
					</div>
				</div>
			</div>
			<div data-v-75aebb7f="" class="pagination el-pagination is-background"><button type="button"
					disabled="disabled" class="btn-prev"><i class="el-icon el-icon-arrow-left"></i></button>
				<ul class="el-pager">
					<li class="number active">1</li>
					<!---->
					<li class="number">2</li>
					<!---->
					<li class="number">3</li>
				</ul><button type="button" class="btn-next"><i class="el-icon el-icon-arrow-right"></i></button>
			</div>
		</div>
	</div>
</template>

<script>
// import {getMomentListByPageNum, likeMoment} from "@/api/moment";

export default {
	name: "Moments",
	data() {
		return {
			// //用localStorage本地存储已点赞的动态id数组
			// likeMomentIds: JSON.parse(window.localStorage.getItem('likeMomentIds') || '[]'),
			// momentList: [],
			// pageNum: 1,
			// totalPage: 0
		}
	},
	created() {
		// this.getMomentList()
	},
	computed: {
		// isLike() {
		// 	return function (id) {
		// 		return this.likeMomentIds.indexOf(id) > -1
		// 	}
		// }
	},
	watch: {
		// likeMomentIds(newValue) {
		// 	//将likeMomentIds最新值的json数据保存到localStorage
		// 	window.localStorage.setItem('likeMomentIds', JSON.stringify(newValue))
		// }
	},
	methods: {
		// getMomentList() {
		// 	//如果有则发送博主身份Token
		// 	const adminToken = window.localStorage.getItem('adminToken')
		// 	const token = adminToken ? adminToken : ''
		// 	getMomentListByPageNum(token, this.pageNum).then(res => {
		// 		if (res.code === 200) {
		// 			this.momentList = res.data.list
		// 			this.totalPage = res.data.totalPage
		// 		} else {
		// 			this.msgError(res.msg)
		// 		}
		// 	}).catch(() => {
		// 		this.msgError("请求失败")
		// 	})
		// },
		// handleCurrentChange(newPage) {
		// 	this.scrollToTop()
		// 	this.pageNum = newPage
		// 	this.getMomentList()
		// },
		// like(id) {
		// 	if (this.likeMomentIds.indexOf(id) > -1) {
		// 		this.$notify({
		// 			title: '不可以重复点赞哦',
		// 			type: 'warning'
		// 		})
		// 		return
		// 	}
		// 	likeMoment(id).then(res => {
		// 		if (res.code === 200) {
		// 			this.$notify({
		// 				title: res.msg,
		// 				type: 'success'
		// 			})
		// 			this.likeMomentIds.push(id)
		// 			this.momentList.forEach(item => {
		// 				if (item.id === id) {
		// 					return item.likes++
		// 				}
		// 			})
		// 		} else {
		// 			this.$notify({
		// 				title: res.msg,
		// 				type: 'warning'
		// 			})
		// 		}
		// 	}).catch(() => {
		// 		this.$notify({
		// 			title: '异常错误',
		// 			type: 'error'
		// 		})
		// 	})
		// }
	}
}
</script>

<style scoped>
.avatar {
	margin-left: -62.5px;
	float: left !important;
}

.avatar img {
	height: 45px;
	width: 45px;
	border-radius: 500px;
}

.moments {
	margin-left: 26px !important;
	padding-left: 40px !important;
	border-left: 1px solid #dee5e7 !important;
}

.moment {
	margin-top: 30px;
}

.moment:first-child {
	margin-top: 0 !important;
}

.card {
	width: 100% !important;
}

.card:before {
	border-width: 0 0 1px 1px !important;
	transform: translateX(-50%) translateY(-50%) rotate(45deg) !important;
	bottom: auto !important;
	right: auto !important;
	top: 22px !important;
	left: 0 !important;
	position: absolute !important;
	content: '' !important;
	background-image: none !important;
	z-index: 2 !important;
	width: 12px !important;
	height: 12px !important;
	transition: background .1s ease !important;
	background-color: inherit !important;
	border-style: solid !important;
	border-color: #d4d4d5 !important;
}

.content.m-top {
	padding: 10px 14px !important;
}

.content .right.floated {
	font-size: 12px !important;
}

.content.typo * {
	font-size: 14px !important;
}

.extra.content {
	padding: 5px 14px !important;
}

.extra.content a {
	color: rgba(0, 0, 0, 0.7) !important;
	font-size: 12px !important;
}

.extra.content a:hover {
	color: red !important;
}

.extra.content .like-color {
	color: red !important;
}

.extra.content i {
	font-size: 12px !important;
}

.pagination {
	text-align: center;
	margin-top: 3em;
}

.privacy {
	background: repeating-linear-gradient(145deg, #f2f2f2, #f2f2f2 15px, #fff 0, #fff 30px) !important;
}
</style>