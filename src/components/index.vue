<template>
    <div>
        <div>
            <header>
                <div class="header">
                    <a href="index.html" class="returnA"><h1 class="htitle">LOGO</h1></a>
                    <div class="hmap" id="gomap"><span class="icon-uniE902"></span>广州</div>
                    <div class="head-input-row head-search">
                        <input id="search" type="search" placeholder="搜索信息" >
                        <span class=" head-icon-left icon-uniE90F"></span>
                        <span class=" head-icon-right icon-uniE939"></span>
                    </div>
                </div>
            </header>
            <div style="height: 2.5rem;"></div>
        </div>

        <div class="all_box">
            <!-- 轮播图 -->
            <div class="m-slider" id="slider">
                <div class="ks_dbox ks_ts">
                    <div class="ks_wrap">
                        <img :src="ks_images"><!--~@/images/j-banner03.jpg-->
                    </div>
                  <!--  <div class="ks_wrap">
                        <img src="~@/images/j-banner02.jpg">
                    </div>
                    <div class="ks_wrap">
                        <img src="~@/images/j-banner03.jpg">
                    </div> -->
                </div>
                <div class="ks-circles"><ul class="ks_wt"></ul></div>
            </div>
            <!-- 轮播图 end-->
            <!-- 功能板块 -->
            <div class="big_button">
                <div class="big_left">
                    <div class="big_left_p"><a href="associationList.html"><span class="icon-uniE92C"></span><h3>我的社区</h3></a></div>
                    <div class="big_left_p2"><a href="login.html"><h3>申请加入</h3></a></div>
                    <div class="ind-bar"></div>
                </div>
                <div class="big_right">
                    <div class="big_rigt_p plate_a fl">
                        <a href="information.html"><span class="icon-17"></span><h3>热门资讯</h3></a>
                        <div class="ind-bar2"></div>
                    </div>
                    <div class="big_rigt_p plate_b fr">
                        <a href="messcenter.html"><span class="icon--01"></span><h3>专家风采</h3></a>
                        <div class="ind-bar3"></div>
                    </div>
                    <div class="big_rigt_p plate_c fl">
                        <a href="firmList.html"><span class="icon-uniE932"></span><h3>企业展示</h3></a>
                        <div class="ind-bar2"></div>
                    </div>
                    <div class="big_rigt_p plate_d fr" >
                        <a href="supply.html"><span class="icomoon icon-uniE93B"></span><h3>采销市场</h3></a>
                        <div class="ind-bar3"></div>
                    </div>
                    <div class="cl"></div>
                </div>
            </div>
            <!-- 功能板块 end-->
            <!-- 会员风采 -->
            <div class="m-Mien">
                <b><em></em>知名专家</b>
                <ul>
                    <li>
                        <a href="MienDetails.html" class="cl">
                            <img src="~@/images/user-img0.jpg">
                            <div class="mienIntro">
                                <h1>郭小帅</h1>
                                <p>机电高材生</p>
                                <p>专注UI设计跟前端</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="javascript:;" class="cl">
                            <img src="~@/images/user-img2.png">
                            <div class="mienIntro">
                                <h1>王二狗</h1>
                                <p>北大青鸟出身</p>
                                <p>Java后台开发，4年经验</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="javascript:;" class="cl">
                            <img src="~@/images/user-img4.png">
                            <div class="mienIntro">
                                <h1>刘美子</h1>
                                <p>广工软件开发专业</p>
                                <p>专业测试，一起来找茬</p>
                            </div>
                        </a>
                    </li>
                </ul>
                <div class="m-Mien-m">
                    <a href="expertType.html">查看更多</a>
                </div>
            </div>
            <!-- 会员风采 end-->
            <!-- 协会活动列表 -->
            <div class="dynamic-list activity-list">
                <div class="dynamic-list-head">
                    <i class="dynamic-i-l icon-uniE93D"></i>
                    <b>热门活动</b>
                    <a href="activityList.html"><i class="dynamic-i-r icomoon icon-uniE906 fr"></i></a>
                </div>
                <ul class="eventreminder">
                    <li>
                        <a href="activity.html">
                            <div class="A-cimg">
                                <img src="~@/images/hd1.jpg">
                                <span class="i-activity p-free">免费</span>
                                <span class="i-activity p-number">246人报名</span>
                                <span class="activity-s activity-s-1">正在报名</span>
                            </div>
                            <div class="eventreminder-list">
                                <p class="activity-h1">广州50Km徒步活动</p>
                                <p class="activity-TimeXh"><span class="fr">5分钟前</span> <span class="event-xh">广州-徒步社</span></p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="activity.html">
                            <div class="A-cimg">
                                <img src="~@/images/hd2.jpg">
                                <span class="i-activity p-number">246人报名</span>
                                <span class="activity-s activity-s-2">活动进行中</span>
                            </div>
                            <div class="eventreminder-list">
                                <p class="activity-h1">精装新品，火热抢购中</p>
                                <p class="activity-TimeXh"><span class="fr">今天 10:40</span> <span class="event-xh">潮妈购物社团</span></p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="activity.html">
                            <div class="A-cimg">
                                <img src="~@/images/hd2.jpg">
                                <span class="i-activity p-free">免费</span>
                                <span class="i-activity p-number">246人报名</span>
                                <span class="activity-s activity-s-3">已报名</span>
                            </div>
                            <div class="eventreminder-list">
                                <p class="activity-h1">火热抢购中,什么什么</p>
                                <p class="activity-TimeXh"><span class="fr">周三 06/01 10:40</span> <span class="event-xh">90后社团</span></p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="activity.html">
                            <div class="A-cimg">
                                <img src="~@/images/hd2.jpg">
                                <span class="i-activity p-free">免费</span>
                                <span class="i-activity p-number">246人报名</span>
                                <span class="activity-s activity-s-4">报名截止</span>
                            </div>
                            <div class="eventreminder-list">
                                <p class="activity-h1">火热抢购中,什么什么</p>
                                <p class="activity-TimeXh"><span class="fr">周三 06/01 10:40</span> <span class="event-xh">80后社团</span></p>
                            </div>
                        </a>
                    </li>
                </ul>
            </div>
            <!-- 协会活动列表 end-->
            <!-- 协会动态列表 -->
            <ul class="dynamic-list">
                <div class="dynamic-list-head">
                    <i class="dynamic-i-l icon-uniE925"></i>
                    <b>热门动态</b>
                    <i class="dynamic-i-r icon-uniE906 fr"></i>
                </div>
                <li>
                    <a href="associationDt.html">
                        <img class="cy-media-object pull-left" src="~@/images/st1.jpg">
                        <div class="cy-media-body">
                            <h3>互联网+ | 发家致富就是这么简单</h3>
                            <p class="cy-ellipsis">雷军说过：“只要站在风口，猪也能飞起来”毫无疑问
                                现在“互联网+”的风头一时无两，究竟是为</p>
                            <p class="cy-ellipsis cy-heatTime">
                                <span><i class="icon-uniE92F"></i>149</span>&nbsp;&nbsp;
                                <span><i class="icon-uniE930"></i>30</span>
                                <span class="fr">5分钟前</span>
                            </p>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="javascript:;">
                        <img class="cy-media-object pull-left" src="~@/images/st2.jpg">
                        <div class="cy-media-body">
                            <h3>桂林八旬渔民模特兄弟 供人拍照红遍全球</h3>
                            <p class="cy-ellipsis">漓江沿岸一带的峰丛，作为桂林喀斯特地貌的一部分，有着诗画般的意境。</p>
                            <p class="cy-ellipsis cy-heatTime">
                                <span><i class="icon-uniE92F"></i>132</span>&nbsp;&nbsp;
                                <span><i class="icon-uniE930"></i>8</span>
                                <span class="fr">2016-5-4</span>
                            </p>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="javascript:;">
                        <img class="cy-media-object pull-left" src="~@/images/st3.jpg">
                        <div class="cy-media-body">
                            <h3>林志玲低胸装搭手保镖出行似“女王”</h3>
                            <p class="cy-ellipsis">早前，林志玲一袭贵妇装出席某颁奖活动。期间，她从贵宾席起身恭谦礼待同为颁奖嘉宾的外籍老高层</p>
                        </div>
                        <p class="cy-ellipsis cy-heatTime">
                            <span><i class="icon-uniE92F"></i>456</span>&nbsp;&nbsp;
                            <span><i class="icon-uniE930"></i>30</span>
                            <span class="fr">2016-5-2</span>
                        </p>
                    </a>
                </li>
                <li>
                    <a href="javascript:;">
                        <img class="cy-media-object pull-left" src="~@/images/st4.jpg">
                        <div class="cy-media-body">
                            <h3>美国大学迎毕业季 学生们把学士帽"玩坏"啦</h3>
                            <p class="cy-ellipsis">这段时间是美国大学的毕业季，美国大学毕业生们为了纪念自己的大学生活，玩出新花样。</p>
                        </div>
                        <p class="cy-ellipsis cy-heatTime">
                            <span><i class="icon-uniE92F"></i>275</span>&nbsp;&nbsp;
                            <span><i class="icon-uniE930"></i>30</span>
                            <span class="fr">2016-4-2</span>
                        </p>
                    </a>
                </li>
            </ul>
        </div>

    </div>
</template>

<script>

    export default {
        name: "index",
        data() {
            return{
                ks_images: require("@/images/j-banner03.jpg"),
                times: null
            }
        },
        components:{

        },
        methods:{
            image(){
            this.times=setInterval();
            }


        }
    }
</script>

<style scoped>
@import "~@/css/index.css";
    @import "~@/css/bass.css";
   @import "~@/assets/fonts/iconfont.css";
</style>