<template>
	<div>
		<div class="ui top attached segment m-padded-lr-big">
			<h2 class="m-text-500" style="text-align: center">帅气的我</h2>
			<meting-js server="netease" type="song" :id="about.musicId" theme="#25CCF7" v-if="about.musicId !== ''">
			</meting-js>
			<div class="typo content m-margin-top-large" v-viewer v-html="about.content"></div>
		</div>
		<!--评论-->


		<div class="ui bottom teal attached segment threaded comments">

			<CommentList :page="1" :blogId="null" v-if="about.commentEnabled === 'true'" />

			<h3 class="ui header" v-else>评论已关闭</h3>
			<meting-js server="netease" type="song" id="1473552803" theme="#25CCF7">
				<div class="aplayer aplayer-withlrc">
					<div class="aplayer-body">
						<div class="aplayer-pic"
							style="background-image: url(&quot;https://api.i-meto.com/meting/api?server=netease&amp;type=pic&amp;id=109951165264681853&amp;auth=f742ae5a4ddbc424d7d640de206b143ac795be72&quot;); background-color: rgb(37, 204, 247);">
							<div class="aplayer-button aplayer-play"><svg xmlns="http://www.w3.org/2000/svg"
									version="1.1" viewBox="0 0 16 31">
									<path
										d="M15.552 15.168q0.448 0.32 0.448 0.832 0 0.448-0.448 0.768l-13.696 8.512q-0.768 0.512-1.312 0.192t-0.544-1.28v-16.448q0-0.96 0.544-1.28t1.312 0.192z">
									</path>
								</svg></div>
						</div>
						<div class="aplayer-info">
							<div class="aplayer-music">
								<span class="aplayer-title">Childhood Dreams</span>
								<span class="aplayer-author"> - Gaminl</span>
							</div>
							<div class="aplayer-lrc">
								<div class="aplayer-lrc-contents"
									style="transform: translateY(0); -webkit-transform: translateY(0);">
									<p class="aplayer-lrc-current">Childhood Dreams</p>

									<p>Hmm mmm mmm</p>

									<p>Hmm mmm mmm</p>

									<p>Hmm mmm mmm</p>

									<p>Hmm mmm mmm</p>

									<p>Hmm mmm mmm</p>

									<p>I dream a hundred dreams a minute (我每分钟要做无数个梦)</p>

									<p>And deep inside what I construct (在内心深处筑起了围墙)</p>

									<p>So there's no use don't even bother (别费力了不要自寻烦恼)</p>

									<p>Tonight is not the night for us (今夜不属于你我二人)</p>

									<p>I have a million shapes a decade (十年间我改变了很多)</p>

									<p>I'm past the point of no return (一切早就无法回头了)</p>

									<p>So don't even call don't even bother (别打我电话不要自寻麻烦)</p>

									<p>Cause I can make your mind concern (因为我能让你牵肠挂肚)</p>

									<p>I'm running faster than before (我比以往更加来去自如)</p>

									<p>Beats and tunes and lovers (这些鼓点曲调和爱人)</p>

									<p>Can not hold me back no more (都已无法阻止我了)</p>

									<p>I work alone (我是个独行侠)</p>

									<p>Is this all I'll ever know (这就是我知道的全部吗)</p>

									<p>And I remember all my childhood dreams (我仍记得自己童年的梦)</p>

									<p>I find it hard to get them out of my mind (难以将它们从脑海中抹去)</p>

									<p>And I remember all my childhood dreams (我仍记得自己童年的梦)</p>

									<p>I find it hard to get them out of my mind (难以将它们从脑海中抹去)</p>

									<p>And I remember all my (我仍记得自己童年的梦)</p>

									<p>So as the night time hits my window (黑夜在敲打我的窗户)</p>

									<p>Sudden move to gain the lights (突然我看到了一片光明)</p>

									<p>Cause I'm not even close to done yet (因为我还没有达成梦想)</p>

									<p>Well I won't leave unto in spite (我绝不会半途而废)</p>

									<p>And when the dawn emerge slowly (当曙光慢慢出现)</p>

									<p>I realized the night has passed (我意识到黑夜已逝)</p>

									<p>The suns I made were visionary (我心中的太阳清晰可见)</p>

									<p>Looking forward to go back (多希望一切能回到过去)</p>

									<p>I'm running faster than before (我比以往更加来去自如)</p>

									<p>Beats and tunes and lovers (这些鼓点曲调和爱人)</p>

									<p>Can not hold me back no more (都已无法阻止我了)</p>

									<p>I work alone (我是个独行侠)</p>

									<p>Is this all I'll ever know (这就是我知道的全部吗)</p>

									<p>And I remember all my childhood dreams (我仍记得自己童年的梦)</p>

									<p>I find it hard to get them out of my mind (难以将它们从脑海中抹去)</p>

									<p>And I remember all my childhood dreams (我仍记得自己童年的梦)</p>

									<p>I find it hard to get them out of my mind (难以将它们从脑海中抹去)</p>

									<p>Hmm mmm mmm~</p>
								</div>
							</div>
							<div class="aplayer-controller">
								<div class="aplayer-bar-wrap">
									<div class="aplayer-bar">
										<div class="aplayer-loaded" style="width: 0.730971%;"></div>
										<div class="aplayer-played" style="width: 0; background: #25CCF7;">
											<span class="aplayer-thumb" style="background: #25CCF7;">
												<span class="aplayer-loading-icon"><svg
														xmlns="http://www.w3.org/2000/svg" version="1.1"
														viewBox="0 0 32 32">
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
											class="aplayer-dtime">02:44</span>
									</span>
									<span class="aplayer-icon aplayer-icon-back">
										<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 32 32">
											<path
												d="M25.468 6.947c-0.326-0.172-0.724-0.151-1.030 0.057l-6.438 4.38v-3.553c0-0.371-0.205-0.71-0.532-0.884-0.326-0.172-0.724-0.151-1.030 0.057l-12 8.164c-0.274 0.186-0.438 0.496-0.438 0.827s0.164 0.641 0.438 0.827l12 8.168c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-3.556l6.438 4.382c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-16.333c0-0.371-0.205-0.71-0.532-0.884z">
											</path>
										</svg>
									</span>
									<span class="aplayer-icon aplayer-icon-play">
										<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 16 31">
											<path
												d="M15.552 15.168q0.448 0.32 0.448 0.832 0 0.448-0.448 0.768l-13.696 8.512q-0.768 0.512-1.312 0.192t-0.544-1.28v-16.448q0-0.96 0.544-1.28t1.312 0.192z">
											</path>
										</svg>
									</span>
									<span class="aplayer-icon aplayer-icon-forward">
										<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 32 32">
											<path
												d="M25.468 6.947c-0.326-0.172-0.724-0.151-1.030 0.057l-6.438 4.38v-3.553c0-0.371-0.205-0.71-0.532-0.884-0.326-0.172-0.724-0.151-1.030 0.057l-12 8.164c-0.274 0.186-0.438 0.496-0.438 0.827s0.164 0.641 0.438 0.827l12 8.168c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-3.556l6.438 4.382c0.169 0.115 0.365 0.174 0.562 0.174 0.16 0 0.321-0.038 0.468-0.116 0.327-0.173 0.532-0.514 0.532-0.884v-16.333c0-0.371-0.205-0.71-0.532-0.884z">
											</path>
										</svg>
									</span>
									<div class="aplayer-volume-wrap">
										<button type="button" class="aplayer-icon aplayer-icon-volume-down"><svg
												xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 28 32">
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
										<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 32 32">
											<path
												d="M0.622 18.334h19.54v7.55l11.052-9.412-11.052-9.413v7.549h-19.54v3.725z">
											</path>
										</svg>
									</button>
									<button type="button" class="aplayer-icon aplayer-icon-loop">
										<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 29 32">
											<path
												d="M9.333 9.333h13.333v4l5.333-5.333-5.333-5.333v4h-16v8h2.667v-5.333zM22.667 22.667h-13.333v-4l-5.333 5.333 5.333 5.333v-4h16v-8h-2.667v5.333z">
											</path>
										</svg>
									</button>
									<button type="button" class="aplayer-icon aplayer-icon-menu">
										<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 22 32">
											<path
												d="M20.8 14.4q0.704 0 1.152 0.48t0.448 1.12-0.48 1.12-1.12 0.48h-19.2q-0.64 0-1.12-0.48t-0.48-1.12 0.448-1.12 1.152-0.48h19.2zM1.6 11.2q-0.64 0-1.12-0.48t-0.48-1.12 0.448-1.12 1.152-0.48h19.2q0.704 0 1.152 0.48t0.448 1.12-0.48 1.12-1.12 0.48h-19.2zM20.8 20.8q0.704 0 1.152 0.48t0.448 1.12-0.48 1.12-1.12 0.48h-19.2q-0.64 0-1.12-0.48t-0.48-1.12 0.448-1.12 1.152-0.48h19.2z">
											</path>
										</svg>
									</button>
									<button type="button" class="aplayer-icon aplayer-icon-lrc">
										<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 32 32">
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
									xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 32 32">
									<path
										d="M22 16l-10.105-10.6-1.895 1.987 8.211 8.613-8.211 8.612 1.895 1.988 8.211-8.613z">
									</path>
								</svg></button></div>
					</div>
					<div class="aplayer-list" style="max-height: 250px">
						<ol style="max-height: 250px">

							<li class="aplayer-list-light">
								<span class="aplayer-list-cur" style="background-color: #25CCF7;"></span>
								<span class="aplayer-list-index">1</span>
								<span class="aplayer-list-title">Childhood Dreams</span>
								<span class="aplayer-list-author">Gaminl</span>
							</li>

						</ol>
					</div>
				</div>
			</meting-js>
			<div class="typo content m-margin-top-large">
				<h3 id="目前可以公开的情报">目前可以公开的情报</h3>
				<ul>
					<li>M E：一只软工大四的蒟蒻</li>
					<li>目标：做最酷的自己</li>
					<li>特征：兴趣至上</li>
					<li>爱好：写Bug、打游戏、看动漫</li>
					<li>性格：不喜约束、比较自私、偶尔emo</li>
				</ul>
				<h3 id="我--博客">我 &amp; 博客</h3>
				<p>生性只对感兴趣的事物充满热情，看到有趣的软件都会情不自禁地分析一波技术栈，可能用到了什么 algorithm，然后自我陶醉😅</p>
				<p>喜欢安静，但喜欢听得劲的电音，节奏控，coding 时喜欢听嗨歌，没事就跟着摇一摇🎵</p>
				<p>奶盖要摇匀了喝！🥛</p>
				<p>世界上只有甜的豆腐脑🤗</p>
				<p><a href="https://github.com/Naccl/NBlog" target="_blank"
						rel="external nofollow noopener">🍓NBlog个人博客系统</a>，本是学习过程中的产物，没想到能受到大家的喜爱，如果你也喜欢本博客，⭐️就是最好的鼓励
				</p>
				<p>博客现在托管在阿里云学生机，因为水管比较小，静态资源托管在 GitHub，通过 jsDelivr CDN减速🚀</p>
				<p>博客源码、部署相关疑难杂症请在 GitHub 提 issue，<strong>请勿</strong>在本博客留言</p>
				<p>如需联系我，请尽量使用 TG 或邮件，thanks（评论我也会收到提醒）</p>
			</div>
			
			
			
			
			
			<div class="">
				<div data-v-d0718afc="">
					<div data-v-18546ec2="" data-v-d0718afc="">
						<div data-v-18546ec2="" class="form">
							<h3> 发表评论 
								 <button type="button" class="el-button m-small el-button--primary el-button--mini"
									style="display: none;">
									
									<span>取消回复</span>
								</button>
								</h3> 
							<form >
								
								<div class="el-textarea textarea">
									<textarea v-model="liuyan" autocomplete="off" rows="5"
										placeholder="评论千万条，友善第一条" maxlength="250" class="el-textarea__inner"
										style="min-height: 35px;">
										</textarea>
										<span class="el-input__count">0/250</span>
								</div>
								
								
					
								
								
								<div class="el-form-item is-required el-form-item--small">
								
									<div class="el-form-item__content">
										<span>
											<div role="tooltip" id="el-popover-9590" aria-hidden="true"
												class="el-popover el-popper el-popover--plain" style="display: none;"
												tabindex="0">
												输入QQ号将自动拉取昵称和头像
											</div>
										</span> 
										
										
										
										<div aria-describedby="el-popover-9590" tabindex="0" >
										
											<input v-model="nicheng" type="text" autocomplete="off" placeholder="昵称（必填）" class="el-input__inner" >
												<span>
													<i></i>
												</span>
											
										</div>
										
									</div>
								</div>
								
								
								
								<div class="el-form-item is-required el-form-item--small">
									
									<div class="el-form-item__content">
										<span>
											<div role="tooltip" id="el-popover-203" aria-hidden="true"
												class="el-popover el-popper el-popover--plain" style="display: none;"
												tabindex="0">
												用于接收回复邮件
											</div>
										</span> 
										<div class="el-input el-input--small el-input--prefix el-popover__reference"
											aria-describedby="el-popover-203" tabindex="0">
										<input  v-model="youxiang" type="text" autocomplete="off" placeholder="邮箱（必填）"
												class="el-input__inner">
												<span class="el-input__prefix">
													<i
													class="el-input__icon el-icon-message"></i>
												
											</span>
											
										</div>
										
									</div>
								</div>
								
								
								
								
								
								
								
								<div class="el-form-item el-form-item--small">
									
									<div class="el-form-item__content">
										<span>
											<div role="tooltip" id="el-popover-8929" aria-hidden="true"
												class="el-popover el-popper el-popover--plain" style="display: none;"
												tabindex="0">
												可以让我参观一下吗😊
											</div>
										</span> 
										<div class="el-input el-input--small el-input--prefix el-popover__reference"
											aria-describedby="el-popover-8929" tabindex="0">
											<input v-model="wangzhi" type="text" autocomplete="off" placeholder="https://（可选）"
												class="el-input__inner">
												<span class="el-input__prefix">
													<i
													class="el-input__icon el-icon-map-location"></i>
												
											</span>
										
										</div>
									
									</div>
								</div>
								<div class="el-form-item el-form-item--small"><label
										class="el-form-item__label">订阅回复</label>
									<div class="el-form-item__content">
										<div role="switch" aria-checked="true" class="el-switch is-checked"><input
												type="checkbox" name="" true-value="true" class="el-switch__input">
											<span class="el-switch__core" style="width: 40px;"></span>
											
										</div>
										
									</div>
								</div> 
								
								
								<div class="el-form-item el-form-item--small">
									
									<div class="el-form-item__content">
										<button @click="fabiao" type="button" class="el-button el-button--primary el-button--medium">
											
											<span>发表评论</span>
										</button>
										
									</div>
								</div>
							</form>
						</div>
						
				

						
						
						<h3 data-v-18546ec2="" class="ui dividing header">Comments | 共 314 条评论<span
								data-v-18546ec2="">（20 条评论被隐藏）</span></h3>
						
						<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-840"
								class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
									data-v-18546ec2=""
									src="https://cdn.naccl.top/blog/comment/avatar/d79ae144-a8c2-45f9-be46-4dc7a5693c0c.jpeg"></a>
							<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
									rel="external nofollow noopener" class="nickname">天官赐福</a>
								
								<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2=""
										class="date">2022-07-21 09:54</strong></div><button data-v-18546ec2=""
									type="button" class="el-button el-button--primary el-button--mini">
									
									<span>回复</span>
								</button>
								<div data-v-18546ec2="" class="text">大佬厉害</div>
							</div>
							
							<div data-v-18546ec2="" class="border"></div>
							
						</div>
						<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-837"
								class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
									data-v-18546ec2=""
									src="https://cdn.naccl.top/blog/comment/avatar/cf18af45-b0f2-4339-819e-2432889b2009.jpeg"></a>
							<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
									rel="external nofollow noopener" class="nickname">HH</a>
								
								<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2=""
										class="date">2022-07-19 12:40</strong></div><button data-v-18546ec2=""
									type="button" class="el-button el-button--primary el-button--mini">
									
									<span>回复</span>
								</button>
								<div data-v-18546ec2="" class="text">哇好棒</div>
							</div>
							
							<div data-v-18546ec2="" class="border"></div>
							
						</div>
						<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-830"
								class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
									data-v-18546ec2="" src="/img/comment-avatar/3.jpg"></a>
							<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
									rel="external nofollow noopener" class="nickname">阿曼</a>
								
								<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2=""
										class="date">2022-07-15 09:52</strong></div><button data-v-18546ec2=""
									type="button" class="el-button el-button--primary el-button--mini">
									
									<span>回复</span>
								</button>
								<div data-v-18546ec2="" class="text">发生发顺丰</div>
							</div>
							
							<div data-v-18546ec2="" class="border"></div>
							
						</div>
						<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-829"
								class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
									data-v-18546ec2=""
									src="https://cdn.naccl.top/blog/comment/avatar/f341b4fb-2e65-4cbe-b672-75754cbd390c.jpeg"></a>
							<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
									rel="external nofollow noopener" class="nickname">TigerChili(龙卷工作室同号）</a>
							
								<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2=""
										class="date">2022-07-15 09:51</strong></div><button data-v-18546ec2=""
									type="button" class="el-button el-button--primary el-button--mini">
									
									<span>回复</span>
								</button>
								<div data-v-18546ec2="" class="text">厉害</div>
							</div>
							
							<div data-v-18546ec2="" class="border"></div>
							
						</div>
						<div data-v-18546ec2="" class="comment"><span data-v-18546ec2="" id="comment-827"
								class="anchor"></span><a data-v-18546ec2="" class="ui circular image avatar"><img
									data-v-18546ec2=""
									src="https://cdn.naccl.top/blog/comment/avatar/334ca656-b381-4bb1-bec0-1d3abc9d6985.jpeg"></a>
							<div data-v-18546ec2="" class="content"><a data-v-18546ec2="" target="_blank"
									rel="external nofollow noopener" class="nickname">X</a>
								
								<div data-v-18546ec2="" class="metadata"><strong data-v-18546ec2=""
										class="date">2022-07-12 19:29</strong></div><button data-v-18546ec2=""
									type="button" class="el-button el-button--primary el-button--mini">
									
									<span>回复</span>
								</button>
								<div data-v-18546ec2="" class="text">可以很强</div>
							</div>
						
							<div data-v-18546ec2="" class="border"></div>
							
						</div>
					</div>
					<div data-v-5bc58a75="" data-v-d0718afc="" class="pagination el-pagination is-background"><button
							type="button" disabled="disabled" class="btn-prev"><i
								class="el-icon el-icon-arrow-left"></i></button>
						<ul class="el-pager">
							<li class="number active">1</li>
							
							<li class="number">2</li>
							<li class="number">3</li>
							<li class="number">4</li>
							<li class="number">5</li>
							<li class="number">6</li>
							<li class="el-icon more btn-quicknext el-icon-more"></li>
							<li class="number">25</li>
						</ul><button type="button" class="btn-next"><i class="el-icon el-icon-arrow-right"></i></button>
					</div> 
				</div>
			</div>
		

		
		
		</div>
	</div>



	
</template>

<script>
// import {getAbout} from "@/api/about";
// import CommentList from "@/components/comment/CommentList";

export default {
	name: "About",
	// components: {CommentList},
	data() {
		return {
			about: {
				title: '',
				musicId: '',
				content: '',
				commentEnabled: 'false'
			},
			liuyan:'',
			nicheng:'',
			youxiang:'',
			wangzhan:''
			
			
			
		}
	},
	created() {
		// this.getData()
	},
	methods: {
		fabiao(){
			if(this.youxiang==''||this.nicheng==''||this.youxiang==''||this.youxiang.replace(/(^\s*)|(\s*$)/g, "")==""){
alert('写点啥提交啊');
 return;
			}else{
				this.$axios({
					methods:'post',
					url:'http://'
				})
			}
			
		}
		// getData() {
		// 	getAbout().then(res => {
		// 		if (res.code === 200) {
		// 			this.about = res.data
		// 		} else {
		// 			this.msgError(res.msg)
		// 		}
		// 	}).catch(() => {
		// 		this.msgError("请求失败")
		// 	})
		// }
	}
}
</script>

<style>
.content ul li {
	letter-spacing: 1px !important;
}

 


</style>