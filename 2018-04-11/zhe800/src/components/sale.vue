<template>
	<div class="goods_page count">
		
			<aside class="pos area">
			        <a href="//shop.zhe800.com" target="_blank">特卖商城</a>
			        <i>&gt;</i> <a target="_blank" href="//shop.zhe800.com/ju_tag/taonanzhuang"> <em class="classification" data-tagid="3004">男装</em></a>
			        <i>&gt;</i> 上装
			        <i>&gt;</i> 南极人男士短袖t恤男装夏季新款圆...
    		</aside>
			<div class="goods count">
				<div class="goods_l">
					<div id="p_box">
						<div id="m_box"></div>
						<img :src="list[this.$route.params.id].src" id="img"/>
						<div id="z_box"></div>
					</div>
					<div id="c_box">
						<img :src="list[this.$route.params.id].src" id="s1"/>
						<img :src="list[this.$route.params.id].src" id="s2"/>
						<img :src="list[this.$route.params.id].src" id="s3"/>
					</div>
					<div id="b_box">
						<img :src="list[this.$route.params.id].src" id="b_img"/>
					</div>
					
				 	<p id="shou_c">
						<a href="#">收藏</a>
						<a href="#">分享</a>
						<a href="#">举报</a>
					</p>
				</div>
				
				<div class="goods_c">
					<h1 id="h_name">{{list[this.$route.params.id].name1}}</h1>
					<div class="goods_bg">
						<p>
							<span id="pic"><b>{{list[this.$route.params.id].name2}}</b></span>
							<span id="i_pic">{{list[this.$route.params.id].name3}}</span>
							<span id="qiandao">
								去客户端签到可领红包
							</span>
						</p> 
						<p>
							<span id="s-1">积分</span>
							<span>Z0最多返20积分∨</span>
							<span>积分可抵订单金额</span>
						</p> 
						<p>
							<span id="s-1">
								优惠
							</span>
							<span> 优惠指定商品满2件8折</span>
						</p> 
					</div>
					<div class="goods_bg1">
						<p>
							<span id="s-1">
								运费
							</span>
							<span> 广东 东莞  至 上海 ∨ 免运费</span>
						</p> 
						<p>
							<span id="s-1">
								服务
							</span>
							<span>折本商品由折800买手砍价</span></p> 
						<p id="col_img">
							<span id="s-1">
								颜色
							</span>
							
						    <img :src="list[this.$route.params.id].src"/>
						    <img :src="list[this.$route.params.id].src"/>
						    <img :src="list[this.$route.params.id].src"/>
						    <span id="">
						    	
						    </span>
						</p> 
						<p>
							<span id="s-1">
								尺码
							</span>
							
							<a href="#">S </a>
							<a href="#">M</a> 
							<a href="#">L</a>
							<a href="#">XL</a>
							<a href="#">XXL</a>
							<a href="#">XXXL</a>
						</p> 
						<p>
							<span id="s-1">
								数量
							</span>
							
							<div class="number">
								<span id="reduce">
									-
								</span>
								<span id="show">
									1 
								</span>
								<span id="add">
									+
								</span>
							</div>   
							<span id="">
								库存1793件
						    </span>
						</p> 
						<p id="btn"><input type="button" name="" id="btn1" value="立即购买" /><router-link tag='input' type="button" to="/goods" id="btn2" value="加入购物车" /></p> 
						<p><span>7天无理由退货</span><span> 退货补贴优惠券</span></p> 
						
					</div>
				</div>
				
				<div class="goods_r">
	               <h3>南极人颖晨昊男装特卖店</h3>
	               <p>信誉：</p>
	               <p>资质： </p>
	               <p>描述综合评分： <span>4.8 ↑</span></p>
	               <p>服务综合评分： <span>4.8 ↑</span></p>
	               <p>发货综合评分： <span>4.8 ↑</span></p>
	               <p>
		               <span id="l_link">
		               		进入店铺 
		               </span>
		               <span id="r_link">
		               		收藏本店
		               </span>
	               </p>
				</div>
			</div>
			
			
			<div class="goods_news">
				<div class="g_left">
					<ul>
						<li>男装热门商品</li>
						<li><a href="#">宝贝详情</a></li>
						<li><a href="#">90天评价 (1)</a></li>
						<li><a href="#">售后保障</a></li>
						<li><a href="#">商品咨询</a></li>
						<li><a href="#">手机购买</a></li>
					</ul>
					<div class="left_news">
						
					</div>
					<div class="center_news">
						<h3>●商品参数</h3>
						
						<p>
							<span id="">
							         品牌：<a>南极人</a>
							</span>
							<span id="">
								面料成分：棉95%,氨纶5%
							</span>
							<span id="">
								厚薄：常规
							</span>
						</p>
						<p>
							<span id="">
							       衣长：常规款
							</span>
							<span id="">
								袖长：短袖
							</span>
							<span id="">
								衣门襟：套头
							</span>
						</p>
						
						<p>
							<span id="">
								洗涤说明：不可漂白
							</span>
						</p>
						<h3>●发货物流</h3>
						<p>
							发货：支付成功后，24小时内发货，因政府“两会”影响，3月2日-3月21日支付成功且收货地址是京、津、冀、新疆、西藏、内蒙等会议影响区域的订单，时效将可能会有延迟
						</p>
						 <p>
						 	物流：商家从 广东/东莞 发货，支持【中通快递】
						 </p>
						<h3>●商品尺码</h3>
						<p>
							TIPS：
						</p>
						<p>
							1.选购时，请综合参考尺码表中各项参数，这将有助于您选择到合适的尺码。</p>
						
						<p>
							2.(只适用于服装)平衡测量自己的合身服装尺寸作参考，对比选购更准确！
						</p>
						 <div class="sizeinfohd">
						 	<p class="text">
						 		<em></em>尺寸适穿表格为真人适穿服装的尺码参考表格，您可参照试穿人合适尺码来选择适合自己的尺码</p>
						 </div>
						 <div class="sizeinfotable ty">
						 	<table>
						 		<tr  class="tit">
						 			<td class="s1">试穿人</td>
						 			<td>身高(cm)</td>
						 			<td>体重(kg)</td>
						 			<td>胸围-腰围-臀围(cm)</td>
						 			<td>试穿码数</td>
						 			<td>试穿感受</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">模特</td>
						 			<td>175</td>
						 			<td>135</td>
						 			<td>标准</td>
						 			<td>XL</td>
						 			<td>合适</td>
						 		</tr>
						 	</table>
						 </div>
						 <div class="sizeinfohd">
						 	<strong>尺码对照表</strong>
						 </div>
						 <div class="sizeinfotable ty scroll_size">
						 	<table>
						 		<tr  class="tit">
						 			<td class="s1">码数</td>
						 			<td>肩宽(cm)</td>
						 			<td>袖长(cm)</td>
						 			<td>衣长(cm)</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">S</td>
						 			<td>40</td>
						 			<td>15</td>
						 			<td>58</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">M</td>
						 			<td>43</td>
						 			<td>17</td>
						 			<td>64</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">L</td>
						 			<td>44</td>
						 			<td>17.5</td>
						 			<td>66</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">XL</td>
						 			<td>45</td>
						 			<td>18</td>
						 			<td>68</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">XXL</td>
						 			<td>46</td>
						 			<td>18.5</td>
						 			<td>70</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">XXXL</td>
						 			<td>47</td>
						 			<td>19</td>
						 			<td>72</td>
						 		</tr>
						 		<tr>
						 			<td colspan="4" class="tipz">
						 				<span>温馨提示：</span>
						 				因个人的体态及尺码测量方式不同，再选择尺码时请务必咨询客服后再下单，如喜欢宽松舒适的体验，请选择大一码!请尊重我们的诚意服务，勿随意给予评价！ 
						 				<span data-picture="//z11.tuanimg.com/imagev2/wxyy/750x1100.7812f4baaef6227c88c2b353681e6ebc.png" href="javascript:void(0);" class="seeSizePicture">
						 					（点击查看尺码测量方式）
						 				</span>
						 			</td>
						 		</tr>
						 	</table>
						 </div>
						 <div class="sizeinfohd">
						 	<p class="text">
						 		<em></em>身高体重对照表是另一款简单直观的服装尺码参考表格，有助于您购买到更合适的尺码，如有特殊需求可根据喜好自行选购
						 	</p>
						 </div>
						 <div class="sizeinfotable tz">
						 	<table>
						 		<tr  class="tit">
						 			<td class="s1">
						 				<div>体重(kg)\身高(cm)</div>
						 			</td>
						 			<td>170</td>
						 			<td>175</td>
						 			<td>180</td>
						 			<td>185</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">60</td>
						 			<td>M</td>
						 			<td>M</td>
						 			<td>L</td>
						 			<td>XL</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">70</td>
						 			<td>L</td>
						 			<td>L</td>
						 			<td>XL</td>
						 			<td>XXL</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">80</td>
						 			<td>XXL</td>
						 			<td>XXL</td>
						 			<td>XXL</td>
						 			<td>XXXL</td>
						 		</tr>
						 		<tr >
						 			<td class="s1">90</td>
						 			<td>XXL</td>
						 			<td>XXXL</td>
						 			<td>XXXL</td>
						 			<td>XXXL</td>
						 		</tr>
						 	</table>
						 </div>

						<h3>●商品价格说明</h3>
						<p>销售价：是买家最终决定是否购买商品的依据。 划横线价格：为参考价，该价格可能是品牌专柜标价、商品吊牌价或由品牌供应商提供的正品零售价（如厂商指导价、建议零售价等）或该商品曾经在折800上曾经展示过的销售价；由于地区、时间的差异性和市场行情波动，此参考价格可能与买家购物时展示的不一致，该价格仅供买家参考。</p>
						<h3>●商品展示</h3>
						
						<p>售后保障
						 7天无理由退货  退货补贴优惠券  商家原因退货，
						运费由商家承担 承诺按时发货</p>
						90天评价
						有内容的评价全部图片(0)追评(0)
						135****4024 
						呵呵呵呵呵
						
						2018-03-11 14:37:49
					</div>
				</div>
				
			</div>
			<ul id="step">
				<li>●商品参数</li>
				<li>●发货物流</li>
				<li>●商品尺码</li>
				<li>●商品展示</li>
				<li>●售后保障</li>
				<li>●90天评价</li>
			</ul>




		</div>
		
		
</template>

<script>
	export default {
		data(){
		return {
			list:[],
		}
	},
	created() {
    // this.$store.dispatch('SHOW_LOADING');
    this.$http({
      url: "./static/deta/close.json",
      // params:{start:1,count:2}
    }).then(
      res =>  {
          this.list=res.data
      }
    )
  },
  
}

</script>


<style scoped>
	/*@import url("../assets/css/Sale.css");*/
	.goods_l{position: relative;background: #fff;}
#p_box {width:300px;height:300px;position:absolute;top:20px;left:20px;}
#p_box img {width:300px;height:300px;opacity: 0.5;}
#b_box{width:300px;height:300px;position:absolute;top:20px;left:360px;display: none;overflow: hidden;}
#b_box img {width:1500px;height:1050px;position: absolute;top: 0;left: 0;}
#z_box {width:100px;height:100px;background:url(https://z3.tuanimg.com/imagev2/trade/800x800.a000572a54b9532955f3b9e1a5913c9a.400x.jpg);background-size:300px 300px;position: absolute;z-index: 3;top:0;left:0;display: none;}
#m_box {width:300px;height:300px;position:absolute;top:0px;left:0px;z-index: 4;}
#c_box {position: absolute;top:320px;left:20px;}
#s1{background: url(https://z3.tuanimg.com/imagev2/trade/800x800.a000572a54b9532955f3b9e1a5913c9a.400x.jpg);opacity:0.5;}
#s2{background: url(https://z2.tuanimg.com/imagev2/trade/800x800.49e579df527da9a193643945bee384b8.58x58.jpg);opacity:0.5;}
#s3{background: url(https://z3.tuanimg.com/imagev2/trade/800x800.79b7a7149e0e448b5b094c09ba83ca69.58x58.jpg);opacity: 1;}
#c_box img{float:left;width:80px;height:80px;margin:10px;background-size: 80px 80px;}


.pos{font-size:14px;color:#999;margin: 10px 0;}
.pos i,.pos em{font-style:normal;}


.goods p{margin:15px 5px;font-size:14px;color:#666;}
.goods p span{margin-right: 20px;}
.goods_bg{background:#fff6eb;padding:5px 5px;}
.goods_bg1{padding:5px 5px;}
.goods_l{float:left;width:400px;}
.goods_c{float:left;width:520px;}
.goods_c h1{font-size:18px;margin: 20px 0;}
.goods_r{float:right;width:200px;text-align: left;border:1px #aaa solid;margin: 20px 0;padding:10px;margin-left: 20px;}
#pic{color:#f00;font-size:20px;}
#i_pic{text-decoration:line-through;}
#s-1{background: #ccc;color:#fff;padding:0 5px;float:left;}
#col_img img{width:30px;float:left;margin: 0 10px;}
.number {float: left;margin-right: 20px;}
.number span{float: left;border:1px #333 solid;width:30px;height:20px;line-height: 20px;text-align: center;}
#btn {padding-top: 20px;}
#btn input{border:none;width:150px;height:50px;font-size:20px;margin: 0 20px;}
#btn input:first-child{border:1px #f00 solid;background:#fff;color:#f00;}
#btn input:last-child{border:none;background:#f00;color:#fff;}

.goods_r{}
.goods_r span{color:#f00}
#l_link,#r_link{border:1px solid #f00;padding:5px 10px;}

#shou_c{float:left;margin-top:430px;margin-left: 10px;}
#shou_c a{color:#aaa;margin-right:20px;}
.g_left ul{width:1000px;overflow: hidden;}
.g_left ul li{float:left;width:150px;height:50px;line-height: 50px;text-align: center;}
.center_news{float:left;width:880px;padding:10px 20px ;color:#666;font-size:14px;}
.center_news>*{margin-top:20px}
.center_news p span{margin-right: 150px;}
.center_news h3{margin-top: 20px;color:#333;}
.center_news taber{   border-collapse:collapse;   border-spacing:0;}
td,th{border-bottom: 1px solid #e3e3e3;border-right:1px solid #e3e3e3;height:40px}
table{border-top: 1px solid #e3e3e3;border-left: 1px solid #e3e3e3;}
#step{float: right;width:100px;border:1px #666 solid;padding:10px}
#step li{margin-top: 20px;margin-left: 10px;;}
#step li:hover{color:#f00;}
.left_news{float:left;width:150px;}
.left_news dl {float:left;width:150px;font-size:10px;}
.left_news dl dt img{width:150px;}
.left_news dl dd p{display:  block;width:150px;overflow: hidden;margin:5px 5px;}
.r_left{float: left;}
.r_right{float: right;color:#666;}	
.p_right{float: right;font-size:10px;color:#666;overflow:hidden}			
.p_left{float: left;font-size:14px;color:#f00;}	

</style>