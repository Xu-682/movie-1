<template>
    <div>
        <el-row style="text-align: left">
            <el-col>
                <h1>豆瓣电影排行榜</h1>
            </el-col>
        </el-row>
        <el-row style="text-align: left;color:#072">
            <el-col>
                <span class="title-col">豆瓣新片榜 · · · · · ·</span>
            </el-col>
        </el-row>
        <div>
            <p class="line"></p>
            <el-row type="flex" justify="center">
                <el-col :span="4" class="picture">
                    <img  src="https://img3.doubanio.com/view/photo/s_ratio_poster/public/p2568902055.webp"/>
                </el-col>
                <el-col :span="20">
                    <div style="text-align: left">
                        <a href="https://movie.douban.com/subject/6981153/">
                            {{movie1.name}}
                        </a>
                    </div>
                    <div style="text-align: left">
                        {{movie1.releaseDate}}
                        {{movie1.pointProjection}}
                        {{movie1.netWork}}
                        {{movie1.cast}}
                    </div>
                    <div style="text-align: left;font-size: 12px;color: #e09015;display: inline-block;float: left;">
                        <el-rate disabled v-model="movie1.scoring.star"></el-rate>
                    </div>
                    <div style="float: left;line-height: 22px">
                        {{movie1.scoring.scor}}
                        <span style="font-size: 13px;color: #666666; float: left;line-height: 22px;">
                            ({{movie1.comment.people}})人评价
                        </span>
                    </div>
                </el-col>
            </el-row>
        </div>


        <div>
            <p class="line"></p>
            <el-row type="flex" justify="center">
                <el-col :span="4" class="picture">
                    <img  src="https://img9.doubanio.com/view/photo/s_ratio_poster/public/p2567198874.webp"/>
                </el-col>
                <el-col :span="20">
                    <div style="text-align: left">
                        <a href="https://movie.douban.com/subject/27119724/">
                            {{movie2.name}}
                        </a>
                    </div>
                    <div style="text-align: left">
                        {{movie2.releaseDate}}
                        {{movie2.pointProjection}}
                        {{movie2.netWork}}
                        {{movie2.cast}}
                    </div>
                    <div style="text-align: left;font-size: 12px;color: #e09015;display: inline-block;float: left;">
                        <el-rate disabled v-model="movie2.scoring.star"></el-rate>
                    </div>
                    <div style="float: left;line-height: 22px">
                        {{movie2.scoring.scor}}
                        <span style="font-size: 13px;color: #666666; float: left;line-height: 22px;">
                            ({{movie2.comment.people}})人评价
                        </span>
                    </div>
                </el-col>
            </el-row>
        </div>


        <div>
            <p class="line"></p>
            <el-row type="flex" justify="center">
                <el-col :span="4" class="picture">
                    <img  src="https://img3.doubanio.com/view/photo/s_ratio_poster/public/p2568902055.webp"/>
                </el-col>
                <el-col :span="20">
                    <div style="text-align: left">
                        <a href="https://movie.douban.com/subject/6981153/">
                            {{movie1.name}}
                        </a>
                    </div>
                    <div style="text-align: left">
                        {{movie1.releaseDate}}
                        {{movie1.pointProjection}}
                        {{movie1.netWork}}
                        {{movie1.cast}}
                    </div>
                    <div style="text-align: left;font-size: 12px;color: #e09015;display: inline-block;float: left;">
                        <el-rate disabled v-model="movie1.scoring.star"></el-rate>
                    </div>
                    <div style="float: left;line-height: 22px">
                        {{movie1.scoring.scor}}
                        <span style="font-size: 13px;color: #666666; float: left;line-height: 22px;">
                            ({{movie1.comment.people}})人评价
                        </span>
                    </div>
                </el-col>
            </el-row>
        </div>


        <div>
            <p class="line"></p>
            <el-row type="flex" justify="center">
                <el-col :span="4" class="picture">
                    <img  src="https://img3.doubanio.com/view/photo/s_ratio_poster/public/p2568902055.webp"/>
                </el-col>
                <el-col :span="20">
                    <div style="text-align: left">
                        <a href="https://movie.douban.com/subject/6981153/">
                            {{movie1.name}}
                        </a>
                    </div>
                    <div style="text-align: left">
                        {{movie1.releaseDate}}
                        {{movie1.pointProjection}}
                        {{movie1.netWork}}
                        {{movie1.cast}}
                    </div>
                    <div style="text-align: left;font-size: 12px;color: #e09015;display: inline-block;float: left;">
                        <el-rate disabled v-model="movie1.scoring.star"></el-rate>
                    </div>
                    <div style="float: left;line-height: 22px">
                        {{movie1.scoring.scor}}
                        <span style="font-size: 13px;color: #666666; float: left;line-height: 22px;">
                            ({{movie1.comment.people}})人评价
                        </span>
                    </div>
                </el-col>
            </el-row>
        </div>


        <div>
            <p class="line"></p>
            <el-row type="flex" justify="center">
                <el-col :span="4" class="picture">
                    <img  src="https://img3.doubanio.com/view/photo/s_ratio_poster/public/p2568902055.webp"/>
                </el-col>
                <el-col :span="20">
                    <div style="text-align: left">
                        <a href="https://movie.douban.com/subject/6981153/">
                            {{movie1.name}}
                        </a>
                    </div>
                    <div style="text-align: left">
                        {{movie1.releaseDate}}
                        {{movie1.pointProjection}}
                        {{movie1.netWork}}
                        {{movie1.cast}}
                    </div>
                    <div style="text-align: left;font-size: 12px;color: #e09015;display: inline-block;float: left;">
                        <el-rate disabled v-model="movie1.scoring.star"></el-rate>
                    </div>
                    <div style="float: left;line-height: 22px">
                        {{movie1.scoring.scor}}
                        <span style="font-size: 13px;color: #666666; float: left;line-height: 22px;">
                            ({{movie1.comment.people}})人评价
                        </span>
                    </div>
                </el-col>
            </el-row>
        </div>


        <div>
            <p class="line"></p>
            <el-row type="flex" justify="center">
                <el-col :span="4" class="picture">
                    <img  src="https://img3.doubanio.com/view/photo/s_ratio_poster/public/p2568902055.webp"/>
                </el-col>
                <el-col :span="20">
                    <div style="text-align: left">
                        <a href="https://movie.douban.com/subject/6981153/">
                            {{movie1.name}}
                        </a>
                    </div>
                    <div style="text-align: left">
                        {{movie1.releaseDate}}
                        {{movie1.pointProjection}}
                        {{movie1.netWork}}
                        {{movie1.cast}}
                    </div>
                    <div style="text-align: left;font-size: 12px;color: #e09015;display: inline-block;float: left;">
                        <el-rate disabled v-model="movie1.scoring.star"></el-rate>
                    </div>
                    <div style="float: left;line-height: 22px">
                        {{movie1.scoring.scor}}
                        <span style="font-size: 13px;color: #666666; float: left;line-height: 22px;">
                            ({{movie1.comment.people}})人评价
                        </span>
                    </div>
                </el-col>
            </el-row>
        </div>


        <div>
            <p class="line"></p>
            <el-row type="flex" justify="center">
                <el-col :span="4" class="picture">
                    <img  src="https://img3.doubanio.com/view/photo/s_ratio_poster/public/p2568902055.webp"/>
                </el-col>
                <el-col :span="20">
                    <div style="text-align: left">
                        <a href="https://movie.douban.com/subject/6981153/">
                            {{movie1.name}}
                        </a>
                    </div>
                    <div style="text-align: left">
                        {{movie1.releaseDate}}
                        {{movie1.pointProjection}}
                        {{movie1.netWork}}
                        {{movie1.cast}}
                    </div>
                    <div style="text-align: left;font-size: 12px;color: #e09015;display: inline-block;float: left;">
                        <el-rate disabled v-model="movie1.scoring.star"></el-rate>
                    </div>
                    <div style="float: left;line-height: 22px">
                        {{movie1.scoring.scor}}
                        <span style="font-size: 13px;color: #666666; float: left;line-height: 22px;">
                            ({{movie1.comment.people}})人评价
                        </span>
                    </div>
                </el-col>
            </el-row>
        </div>
    </div>
</template>
<script>
    import ElRate from "../../node_modules/element-ui/packages/rate/src/main";
    import ElCol from "element-ui/packages/col/src/col";
    import ElProgress from "../../node_modules/element-ui/packages/progress/src/progress";
    import ElButton from "../../node_modules/element-ui/packages/button/src/button";
    import ElRow from "element-ui/packages/row/src/row";
    export default{
        components: {
            ElRow,
            ElButton,
            ElProgress,
            ElCol,
            ElRate},
    data(){
            return{
                movie1:{
                    name:'爱尔兰人 / 爱尔兰杀手(港) / 听说你刷房子了',
                    releaseDate:'2019-09-27(纽约电影节)',
                    pointProjection:'2019-11-01(美国点映) ',
                    netWork:'2019-11-27(美国网络)',
                    cast:'/罗伯特·德尼罗/阿尔·帕西诺/ 乔·佩西 / 安娜·帕奎因 / 杰西·普莱蒙 / 哈威·凯特尔 / 斯蒂芬·格拉汉姆 / 鲍比·坎纳瓦尔 /杰克·休斯顿 / 阿莱卡萨·帕拉迪诺 / 凯瑟琳·纳杜奇...',
                    scoring:{
                        star:4.5,
                        scor:9.1,
                    },
                    comment:{
                        people:46812,
                    },
                },

                movie2:{
                    name:'小丑起源电影：罗密欧 / Romeo',
                    releaseDate:'2019-08-31(威尼斯电影节)',
                    pointProjection:'2019-10-04(美国点映) ',
                    netWork:'2019-11-27(美国网络)',
                    cast:'/ 杰昆·菲尼克斯/ /罗伯特·德尼罗/ 马克·马龙 / 莎姬·贝兹  / 谢伊·惠格姆/ 弗兰西丝·康罗伊 / 布莱恩·考伦/ 布莱恩·泰里·亨利 /布莱特·卡伦 / 道格拉斯·霍奇斯 / 格伦·弗莱施勒...',
                    scoring:{
                        star:4.5,
                        score:8.8,
                    },
                    comment:{
                        people:379637
                    }
            }
        }
    }
    }

</script>
<style scoped>
    p{border-bottom: 1px dashed #DDDDDD;}
    .picture img{
        width:75px;
    }
</style>