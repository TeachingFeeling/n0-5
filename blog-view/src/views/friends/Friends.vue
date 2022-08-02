<template>
	<div>
		<div class="ui top attached segment" style="text-align: center">
			<h2 class="m-text-500">小伙伴们</h2>
		</div>
		<!-- <div class="ui attached segment">
			<div class="ui link three doubling cards">
				<a :href="item.website" target="_blank" rel="external nofollow noopener" class="card" :style="randomRGB()"
				   v-for="(item,index) in friendList" :key="index" @click="addViews(item.nickname)">
					<div class="image">
						<img :src="item.avatar" onerror="this.src = '/img/error.png'">
					</div>
					<div class="content">
						<div class="header">{{ item.nickname }}</div>
						<div class="description">{{ item.description }}</div>
					</div>
				</a>
			</div>
		</div> -->
		<div data-v-38ac0e10="" class="ui attached segment">
			<div data-v-38ac0e10="" class="ui link three doubling cards"><a data-v-38ac0e10=""
					href="http://lzmandzcc.com" target="_blank" rel="external nofollow noopener" class="card"
					style="background-color: rgb(52, 73, 94);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10="" src="/img/error.png"
							onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">LZM and ZCC</div>
						<div data-v-38ac0e10="" class="description">忘掉腼腆，转过脸来，把一串疯话，说在你面前。</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://luotianyi.vc/" target="_blank" rel="external nofollow noopener"
					class="card" style="background-color: rgb(46, 204, 113);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10=""
							src="https://static.lty.fun/weblogo/my.jpg" onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">Luminous’ Home</div>
						<div data-v-38ac0e10="" class="description">记录生活中的点滴</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://raxcl.cn" target="_blank" rel="external nofollow noopener"
					class="card" style="background-color: rgb(247, 159, 31);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10="" src="/img/error.png"
							onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">raxcl</div>
						<div data-v-38ac0e10="" class="description">我有足够的积累，但又一直在路上，所以会有无限的可能</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://grimoire.cn" target="_blank" rel="external nofollow noopener"
					class="card" style="background-color: rgb(247, 159, 31);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10=""
							src="https://s1.ax1x.com/2020/03/26/G93rfs.jpg" onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">五葉魔法書</div>
						<div data-v-38ac0e10="" class="description">一个神秘的人</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://yoyling.com" target="_blank" rel="external nofollow noopener"
					class="card" style="background-color: rgb(247, 159, 31);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10="" src="https://yoyling.com/favicon.png"
							onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">YOYLING</div>
						<div data-v-38ac0e10="" class="description">大道至简 大简至极</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://www.cnblogs.com/starry7" target="_blank"
					rel="external nofollow noopener" class="card" style="background-color: rgb(155, 89, 182);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10="" src="/img/error.png"
							onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">Starry</div>
						<div data-v-38ac0e10="" class="description">Sometimes ever, Sometimes never</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://kudaompq.top" target="_blank" rel="external nofollow noopener"
					class="card" style="background-color: rgb(231, 76, 60);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10="" src="/img/error.png"
							onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">Kudaompq</div>
						<div data-v-38ac0e10="" class="description">Do Yourself</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://ryanyang.cn" target="_blank" rel="external nofollow noopener"
					class="card" style="background-color: rgb(241, 196, 15);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10="" src="/img/error.png"
							onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">ryan</div>
						<div data-v-38ac0e10="" class="description">一位智慧的阿拉伯诗人曾经说过</div>
					</div>
				</a><a data-v-38ac0e10="" href="https://thiscute.world/" target="_blank"
					rel="external nofollow noopener" class="card" style="background-color: rgb(241, 196, 15);">
					<div data-v-38ac0e10="" class="image"><img data-v-38ac0e10=""
							src="https://thiscute.world/avatar/myself.jpg" onerror="this.src = '/img/error.png'"></div>
					<div data-v-38ac0e10="" class="content">
						<div data-v-38ac0e10="" class="header">This Cute World</div>
						<div data-v-38ac0e10="" class="description">赞美快乐~</div>
					</div>
				</a></div>
		</div>
		<!--页面描述-->
		<!-- <div class="ui teal attached segment">
			<div class="typo content" v-viewer v-html="info.content"></div>
		</div> -->
		<div data-v-38ac0e10="" class="ui teal attached segment">
			<div data-v-38ac0e10="" class="typo content">
				<p>随机排序，不分先后。欢迎交换友链~(￣▽￣)~*</p>
				<ul>
					<li>昵称：Naccl</li>
					<li>一句话：游龙当归海，海不迎我自来也。</li>
					<li>网址：<a href="https://naccl.top" target="_blank"
							rel="external nofollow noopener">https://naccl.top</a></li>
					<li>头像URL：<a href="https://naccl.top/img/avatar.jpg" target="_blank"
							rel="external nofollow noopener">https://naccl.top/img/avatar.jpg</a></li>
				</ul>
				<p>仅凭个人喜好添加友链，请在收到我的回复邮件后再于贵站添加本站链接。原则上已添加的友链不会删除，如果你发现自己被移除了，恕不另行通知，只需和我一样做就好。</p>
			</div>
		</div>
		<!--评论-->
		<div class="ui bottom teal attached segment threaded comments">
			<CommentList :page="2" :blogId="null" v-if="info.commentEnabled" />
			<h3 class="ui header" v-else>评论已关闭</h3>
		</div>
		<div data-v-38ac0e10="" class="ui bottom teal attached segment threaded comments">
			<div data-v-d0718afc="" data-v-38ac0e10="">
				<div data-v-18546ec2="" data-v-d0718afc="">
					<div data-v-18546ec2="" class="form">
						<h3> 发表评论 <button type="button" class="el-button m-small el-button--primary el-button--mini"
								style="display: none;">
								<!---->
								<!----><span>取消回复</span>
							</button></h3>
						<form class="el-form el-form--inline">
							<div class="el-textarea textarea"><textarea autocomplete="off" rows="5"
									placeholder="评论千万条，友善第一条" maxlength="250" class="el-textarea__inner"
									style="min-height: 35px;"></textarea><span class="el-input__count">0/250</span>
							</div>
							<div class="el-form-item el-form-item--small emoji"><img
									src="https://cdn.naccl.top/blog/img/paopao/1.png">
								<div class="mask" style="display: none;"></div>
								<div class="emoji-box" style="display: none;">
									<div class="emoji-title"><span>tv_小电视</span></div>
									<div class="emoji-wrap">
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/1.png"
												title="@[tv_白眼]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/2.png"
												title="@[tv_doge]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/3.png"
												title="@[tv_坏笑]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/4.png"
												title="@[tv_难过]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/5.png"
												title="@[tv_生气]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/6.png"
												title="@[tv_委屈]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/7.png"
												title="@[tv_斜眼笑]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/8.png"
												title="@[tv_呆]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/9.png"
												title="@[tv_发怒]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/10.png"
												title="@[tv_惊吓]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/11.png"
												title="@[tv_呕吐]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/12.png"
												title="@[tv_思考]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/13.png"
												title="@[tv_微笑]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/14.png"
												title="@[tv_疑问]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/15.png"
												title="@[tv_大哭]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/16.png"
												title="@[tv_鼓掌]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/17.png"
												title="@[tv_抠鼻]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/18.png"
												title="@[tv_亲亲]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/19.png"
												title="@[tv_调皮]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/20.png"
												title="@[tv_笑哭]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/21.png"
												title="@[tv_晕]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/22.png"
												title="@[tv_点赞]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/23.png"
												title="@[tv_害羞]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/24.png"
												title="@[tv_睡着]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/25.png"
												title="@[tv_色]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/26.png"
												title="@[tv_吐血]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/27.png"
												title="@[tv_无奈]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/28.png"
												title="@[tv_再见]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/29.png"
												title="@[tv_流汗]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/30.png"
												title="@[tv_偷笑]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/31.png"
												title="@[tv_抓狂]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/32.png"
												title="@[tv_黑人问号]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/33.png"
												title="@[tv_困]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/34.png"
												title="@[tv_打脸]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/35.png"
												title="@[tv_闭嘴]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/36.png"
												title="@[tv_鄙视]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/37.png"
												title="@[tv_腼腆]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/38.png"
												title="@[tv_馋]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/39.png"
												title="@[tv_可爱]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/40.png"
												title="@[tv_发财]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/41.png"
												title="@[tv_生病]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/42.png"
												title="@[tv_流鼻血]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/43.png"
												title="@[tv_尴尬]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/44.png"
												title="@[tv_大佬]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/45.png"
												title="@[tv_流泪]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/46.png"
												title="@[tv_冷漠]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/47.png"
												title="@[tv_皱眉]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/48.png"
												title="@[tv_鬼脸]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/49.png"
												title="@[tv_调侃]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/tv/50.png"
												title="@[tv_目瞪口呆]"></div>
									</div>
									<div class="emoji-wrap" style="display: none;">
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/1.png"
												title="@[aru_高兴]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/2.png"
												title="@[aru_皱眉]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/3.png"
												title="@[aru_阴笑]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/4.png"
												title="@[aru_鄙视]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/5.png"
												title="@[aru_邪恶]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/6.png"
												title="@[aru_大囧]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/7.png"
												title="@[aru_惊喜]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/8.png"
												title="@[aru_小眼睛]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/9.png"
												title="@[aru_小怒]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/10.png"
												title="@[aru_无语]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/11.png"
												title="@[aru_傻笑]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/12.png"
												title="@[aru_期待]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/13.png"
												title="@[aru_得逞]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/14.png"
												title="@[aru_呲牙]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/15.png"
												title="@[aru_喜极而泣]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/16.png"
												title="@[aru_晕死]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/17.png"
												title="@[aru_脸红]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/18.png"
												title="@[aru_亲亲]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/19.png"
												title="@[aru_狂汗]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/20.png"
												title="@[aru_困]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/21.png"
												title="@[aru_饥饿]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/22.png"
												title="@[aru_得意]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/23.png"
												title="@[aru_抠鼻]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/24.png"
												title="@[aru_抽烟]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/25.png"
												title="@[aru_内伤]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/26.png"
												title="@[aru_口水]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/27.png"
												title="@[aru_吐]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/28.png"
												title="@[aru_流鼻涕]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/29.png"
												title="@[aru_绷带]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/30.png"
												title="@[aru_吐舌]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/31.png"
												title="@[aru_口罩]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/32.png"
												title="@[aru_不说话]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/33.png"
												title="@[aru_不出所料]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/34.png"
												title="@[aru_装大款]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/35.png"
												title="@[aru_尴尬]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/36.png"
												title="@[aru_喷水]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/37.png"
												title="@[aru_喷血]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/38.png"
												title="@[aru_咽气]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/39.png"
												title="@[aru_哼小曲]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/40.png"
												title="@[aru_吹泡泡]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/41.png"
												title="@[aru_愤怒]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/42.png"
												title="@[aru_冻住]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/43.png"
												title="@[aru_赞一个]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/44.png"
												title="@[aru_差评]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/45.png"
												title="@[aru_中指]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/46.png"
												title="@[aru_哦耶]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/47.png"
												title="@[aru_拳头]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/48.png"
												title="@[aru_手掌]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/49.png"
												title="@[aru_就是你]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/50.png"
												title="@[aru_过来]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/51.png"
												title="@[aru_吃雪糕]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/52.png"
												title="@[aru_吃香蕉]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/53.png"
												title="@[aru_ok]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/54.png"
												title="@[aru_看不见]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/55.png"
												title="@[aru_无所谓]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/56.png"
												title="@[aru_欢呼]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/57.png"
												title="@[aru_偷笑]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/58.png"
												title="@[aru_无奈]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/59.png"
												title="@[aru_害羞]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/60.png"
												title="@[aru_打脸]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/61.png"
												title="@[aru_想一想]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/62.png"
												title="@[aru_嘘]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/63.png"
												title="@[aru_烧香]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/64.png"
												title="@[aru_抱拳]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/65.png"
												title="@[aru_鼓掌]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/66.png"
												title="@[aru_观察]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/67.png"
												title="@[aru_锁眉]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/68.png"
												title="@[aru_黑线]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/69.png"
												title="@[aru_汗]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/70.png"
												title="@[aru_哭泣]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/71.png"
												title="@[aru_阴暗]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/72.png"
												title="@[aru_暗地观察]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/73.png"
												title="@[aru_潜水]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/74.png"
												title="@[aru_蜡烛]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/75.png"
												title="@[aru_投降]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/76.png"
												title="@[aru_吐血倒地]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/77.png"
												title="@[aru_便便]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/78.png"
												title="@[aru_长草]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/79.png"
												title="@[aru_绿帽子]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/80.png"
												title="@[aru_注意安全]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/81.png"
												title="@[aru_被砍]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/82.png"
												title="@[aru_捶打]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/83.png"
												title="@[aru_肿包]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/84.png"
												title="@[aru_坐等]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/85.png"
												title="@[aru_看热闹]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/86.png"
												title="@[aru_深思]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/aru/87.png"
												title="@[aru_被监视]"></div>
									</div>
									<div class="emoji-wrap" style="display: none;">
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/1.png"
												title="@[p_滑稽]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/2.png"
												title="@[p_不高兴]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/3.png"
												title="@[p_乖]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/4.png"
												title="@[p_冷]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/5.png"
												title="@[p_勉强]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/6.png"
												title="@[p_吐]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/7.png"
												title="@[p_吐舌]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/8.png"
												title="@[p_呵呵]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/9.png"
												title="@[p_呼]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/10.png"
												title="@[p_咦]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/11.png"
												title="@[p_哈哈]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/12.png"
												title="@[p_啊]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/13.png"
												title="@[p_喷]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/14.png"
												title="@[p_太开心]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/15.png"
												title="@[p_委屈]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/16.png"
												title="@[p_开心]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/17.png"
												title="@[p_怒]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/18.png"
												title="@[p_惊哭]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/19.png"
												title="@[p_惊讶]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/20.png"
												title="@[p_汗]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/21.png"
												title="@[p_泪]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/22.png"
												title="@[p_狂汗]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/23.png"
												title="@[p_生气]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/24.png"
												title="@[p_疑问]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/25.png"
												title="@[p_真棒]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/26.png"
												title="@[p_睡觉]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/27.png"
												title="@[p_笑眼]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/28.png"
												title="@[p_花心]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/29.png"
												title="@[p_鄙视]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/30.png"
												title="@[p_酷]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/31.png"
												title="@[p_钱]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/32.png"
												title="@[p_阴险]"></div>
										<div class="emoji-list"><img src="https://cdn.naccl.top/blog/img/paopao/33.png"
												title="@[p_黑线]"></div>
									</div>
									<div class="emoji-tabs"><a class="tab-link on"><img
												src="https://cdn.naccl.top/blog/img/tv/1.png"></a><a
											class="tab-link"><img src="https://cdn.naccl.top/blog/img/aru/1.png"></a><a
											class="tab-link"><img src="https://cdn.naccl.top/blog/img/paopao/1.png"></a>
									</div>
								</div>
							</div>
							<div class="el-form-item is-required el-form-item--small">
								<!---->
								<div class="el-form-item__content"><span>
										<div role="tooltip" id="el-popover-8701" aria-hidden="true"
											class="el-popover el-popper el-popover--plain" style="display: none;"
											tabindex="0">
											<!---->输入QQ号将自动拉取昵称和头像
										</div>
									</span>
									<div class="el-input el-input--small el-input--prefix el-popover__reference"
										aria-describedby="el-popover-8701" tabindex="0">
										<!----><input type="text" autocomplete="off" placeholder="昵称（必填）"
											class="el-input__inner"><span class="el-input__prefix"><i
												class="el-input__icon el-icon-user"></i>
											<!---->
										</span>
										<!---->
										<!---->
										<!---->
									</div>
									<!---->
								</div>
							</div>
							<div class="el-form-item is-required el-form-item--small">
								<!---->
								<div class="el-form-item__content"><span>
										<div role="tooltip" id="el-popover-121" aria-hidden="true"
											class="el-popover el-popper el-popover--plain" style="display: none;"
											tabindex="0">
											<!---->用于接收回复邮件
										</div>
									</span>
									<div class="el-input el-input--small el-input--prefix el-popover__reference"
										aria-describedby="el-popover-121" tabindex="0">
										<!----><input type="text" autocomplete="off" placeholder="邮箱（必填）"
											class="el-input__inner"><span class="el-input__prefix"><i
												class="el-input__icon el-icon-message"></i>
											<!---->
										</span>
										<!---->
										<!---->
										<!---->
									</div>
									<!---->
								</div>
							</div>
							<div class="el-form-item el-form-item--small">
								<!---->
								<div class="el-form-item__content"><span>
										<div role="tooltip" id="el-popover-4907" aria-hidden="true"
											class="el-popover el-popper el-popover--plain" style="display: none;"
											tabindex="0">
											<!---->可以让我参观一下吗😊
										</div>
									</span>
									<div class="el-input el-input--small el-input--prefix el-popover__reference"
										aria-describedby="el-popover-4907" tabindex="0">
										<!----><input type="text" autocomplete="off" placeholder="https://（可选）"
											class="el-input__inner"><span class="el-input__prefix"><i
												class="el-input__icon el-icon-map-location"></i>
											<!---->
										</span>
										<!---->
										<!---->
										<!---->
									</div>
									<!---->
								</div>
							</div>
							<div class="el-form-item el-form-item--small"><label
									class="el-form-item__label">订阅回复</label>
								<div class="el-form-item__content">
									<div role="switch" aria-checked="true" class="el-switch is-checked"><input
											type="checkbox" name="" true-value="true" class="el-switch__input">
										<!----><span class="el-switch__core" style="width: 40px;"></span>
										<!---->
									</div>
									<!---->
								</div>
							</div>
							<div class="el-form-item el-form-item--small">
								<!---->
								<div class="el-form-item__content"><button type="button"
										class="el-button el-button--primary el-button--medium">
										<!---->
										<!----><span>发表评论</span>
									</button>
									<!---->
								</div>
							</div>
						</form>
					</div>
					<h3 data-v-18546ec2="" class="ui dividing header">Comments | 共 44 条评论<span data-v-18546ec2="">（8
							条评论被隐藏）</span></h3>
					<!---->
					<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-824"
							class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
								data-v-18546ec2="" src="/img/comment-avatar/4.jpg"></a>
						<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" href="https://www.lbzi.cn/"
								target="_blank" rel="external nofollow noopener" class="nickname">LBZI</a>
							<!---->
							<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2="" class="date">2022-07-05
									18:07</strong></div><button data-v-18546ec2="" type="button"
								class="el-button el-button--primary el-button--mini">
								<!---->
								<!----><span>回复</span>
							</button>
							<div data-v-18546ec2="" class="text">博客名称：LBZICNの小站
								博客链接：https://www.lbzi.cn/
								博客头像：https://www.lbzi.cn/tx.jpg
								博客描述：发现更多乐趣！</div>
						</div>
						<!---->
						<div data-v-18546ec2="" class="border"></div>
						<!---->
					</div>
					<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-821"
							class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
								data-v-18546ec2=""
								src="https://cdn.naccl.top/blog/comment/avatar/6a08d261-15c2-4508-a046-e2b072505b4d.jpeg"></a>
						<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
								rel="external nofollow noopener" class="nickname">pony</a>
							<!---->
							<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2="" class="date">2022-07-04
									20:53</strong></div><button data-v-18546ec2="" type="button"
								class="el-button el-button--primary el-button--mini">
								<!---->
								<!----><span>回复</span>
							</button>
							<div data-v-18546ec2="" class="text">牛逼</div>
						</div>
						<!---->
						<div data-v-18546ec2="" class="border"></div>
						<!---->
					</div>
					<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-820"
							class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
								data-v-18546ec2=""
								src="https://cdn.naccl.top/blog/comment/avatar/32872af5-c6e7-4d04-90d3-80df12f3ce71.jpeg"></a>
						<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
								rel="external nofollow noopener" class="nickname">此燃</a>
							<!---->
							<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2="" class="date">2022-07-04
									20:47</strong></div><button data-v-18546ec2="" type="button"
								class="el-button el-button--primary el-button--mini">
								<!---->
								<!----><span>回复</span>
							</button>
							<div data-v-18546ec2="" class="text">牛逼牛逼牛逼牛逼牛逼牛逼</div>
						</div>
						<!---->
						<div data-v-18546ec2="" class="border"></div>
						<!---->
					</div>
					<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-814"
							class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
								data-v-18546ec2="" src="/img/comment-avatar/6.jpg"></a>
						<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
								rel="external nofollow noopener" class="nickname">十二</a>
							<!---->
							<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2="" class="date">2022-06-25
									20:07</strong></div><button data-v-18546ec2="" type="button"
								class="el-button el-button--primary el-button--mini">
								<!---->
								<!----><span>回复</span>
							</button>
							<div data-v-18546ec2="" class="text">厉害啊 </div>
						</div>
						<!---->
						<div data-v-18546ec2="" class="border"></div>
						<!---->
					</div>
					<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-804"
							class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
								data-v-18546ec2=""
								src="https://cdn.naccl.top/blog/comment/avatar/4777c49c-a728-49f8-b61b-38e14a10e07f.jpeg"></a>
						<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
								rel="external nofollow noopener" class="nickname">屁</a>
							<!---->
							<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2="" class="date">2022-06-19
									14:24</strong></div><button data-v-18546ec2="" type="button"
								class="el-button el-button--primary el-button--mini">
								<!---->
								<!----><span>回复</span>
							</button>
							<div data-v-18546ec2="" class="text"><img src="https://cdn.naccl.top/blog/img/tv/1.png"><img
									src="https://cdn.naccl.top/blog/img/aru/2.png"><img
									src="https://cdn.naccl.top/blog/img/paopao/6.png"></div>
						</div>
						<!---->
						<div data-v-18546ec2="" class="border"></div>
						<!---->
					</div>
				</div>
				<div data-v-5bc58a75="" data-v-d0718afc="" class="pagination el-pagination is-background"><button
						type="button" disabled="disabled" class="btn-prev"><i
							class="el-icon el-icon-arrow-left"></i></button>
					<ul class="el-pager">
						<li class="number active">1</li>
						<!---->
						<li class="number">2</li>
						<li class="number">3</li>
						<!---->
						<li class="number">4</li>
					</ul><button type="button" class="btn-next"><i class="el-icon el-icon-arrow-right"></i></button>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
// import {getData, addViewsByNickname} from "@/api/friend";
// import CommentList from "@/components/comment/CommentList";

export default {
	name: "Friends",
	// 	components: {CommentList},
	data() {
		return {
			friendList: [],
			bgColor: [
				'#1abc9c', '#2ecc71', '#3498db', '#9b59b6',
				'#34495e', '#f1c40f', '#e67e22', '#e74c3c',
				'#ee5a24', '#9980fa', '#8c7ae6', '#f79f1f'
			],
			info: {
				content: '',
				commentEnabled: false
			}
		}
	},
	// 	created() {
	// 		this.getData()
	// 	},
	// 	methods: {
	// 		getData() {
	// 			getData().then(res => {
	// 				if (res.code === 200) {
	// 					this.friendList = res.data.friendList
	// 					this.info = res.data.friendInfo
	// 				} else {
	// 					this.msgError(res.msg)
	// 				}
	// 			}).catch(() => {
	// 				this.msgError("请求失败")
	// 			})
	// 		},
	// 		addViews(nickname) {
	// 			addViewsByNickname(nickname)
	// 		},
	// 		randomRGB() {
	// 			const index = Math.floor((Math.random() * this.bgColor.length))
	// 			return {backgroundColor: this.bgColor[index]}
	// 		}
	// }
}
</script>

<style scoped>
.card .image {
	width: 70px !important;
	margin: 10px auto 0px;
	background: unset !important;
}

.card .image img {
	border-radius: 100% !important;
	width: 70px !important;
	height: 70px !important;
}

.card .content {
	text-align: center;
	padding: 10px 14px !important;
	border-top: 0 !important;
}

.card .content * {
	color: #fff !important;
}

.card .content .header {
	font-size: 16px !important;
}

.card .content .description {
	font-size: 12px !important;
}

.card .content .description {
	margin-top: 5px !important;
	margin-bottom: 7px;
}
</style>