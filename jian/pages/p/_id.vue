<template>
    <div>
        <my-header></my-header>
        <div class="note">
            <div class="post">
                <!--文章正文-->
                <div class="article">
                    <h1 class="title">记观《解忧杂货铺》</h1>
                    <div class="author">
                        <div class="avatar">
                            <img src="~/assets/img/default-avatar.jpg">
                        </div>
                        <div class="info">
                            <nuxt-link class="name" to="name">
                                秘名
                            </nuxt-link>
                            <a href="#" class="btn btn-follow">
                                <i class="fa fa-plus"></i>
                                <span>关注</span>
                            </a>
                            <div class="meta">
                                <span class="publish-time">
                                    2018.03.01 21:09
                                </span>
                                <span class="wordage">
                                    字数 1083
                                </span>
                                <span class="view-count">
                                    阅读 12
                                </span>
                                <span class="comment-count">
                                    评论 0
                                </span>
                                <span class="like-count">
                                    喜欢 10
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="show-content">
                        <div class="show-content-free">
                            <p>很早就有《解忧杂货铺》这本书，翻看了几页，一直不能投入于是便放下。春节期间，与一位小学五年级的小帅哥聊天，说到他在看此书，我困惑的说看不下去，他给的建议是：阿姨，你可以先看电影，再看书，很好看。于是当天是晚上我便看完了找到并看完了该片。<br></p><p> 作者是日本人，日本和中国都有把他搬上宽荧幕。我看的是中国拍的。我这样一位四十岁的中年妇女当看到一开场是热巴和王俊凯这两个当红小明星，真想马上暂停。拿起手机问问小朋友：你不是因为王俊凯和热巴才喜欢《杂货铺》的吧？好了，演员养眼总是好的，继续看，嘿嘿！<br></p><p>故事的开端是三个年轻人做了错事，因为害怕，无意中躲进了一栋荒废了的房子。在天渐渐黑了的时候，突然从房子前门信口扔进来一封信。信的内容是一位因生活所迫当了舞女的女孩对现实生活越来越迷茫，想得到人生指点。三个年轻人看到信后不知所措，但之后他们在房子中发现了许多陈旧的信件和报纸，从中明白了许多年前这个小房子中发生的故事。<br></p><p>房子以前是一个小杂货铺，主人是一位善良的老爷爷。他多年来一直在帮助那些心中有困惑的人，希望带领他们走出生活的灰暗时期，走出心中的阴霾。人们从房子的前门塞进信来，讲述困惑，老爷爷回信后放在后门的信箱，等待人们取走。老爷爷也迷茫过，他的信件，他的话语是否真的帮到了人们？或者他的话语是否正确的呢？ <br></p><p>小小的杂货铺成了人们心中的解忧杂货铺，四面八方的人们把信投递到这里，并得到了一位善良爷爷的帮助，爷爷保守这所有来信人的秘密，一直到离开人世都惦记着他回过信的人们的生活是否幸福了，是否开心了。爷爷希望二十年后的一天能够打开时光通道，看看当年帮到的人们的现状。<br></p><p>今天正是时光通道打开的那天，被三个年轻人无意赶上。他们从当年写信人的生活轨迹发现了许多人现在不仅走出心中的阴影，而且已经小有成就。从你来我往的信中看，他们听从了爷爷的话，一路走来，春暖花开。<br></p><p>于是三个年轻人想既然正巧遇到了来信，就要给人家回信。他们因为回信的内容和语气激烈争吵，最后回了一封遵从三个人内心的信，希望女孩离开复杂纷乱的舞厅，继续学习，找到全新的自我。没想到后来，那个收信的女孩真的照做了，并且之后的人生真的成功了！<br></p><p>在影片的结尾，已经“成仙”的老爷爷说：“其实人们在给他寄信的时候心中是有答案的，而且答案都是光明的、向上的”，爷爷的回信只是让他们更加坚信了自己的决定，让他们感觉到自己的秘密分享给了一个懂得自己的人，并且得到了他的支持。<br></p><p>三个犯了错的年轻人在一个荒废了的小房子中度过了神奇的一天后，也找到了人生的方向，他们迎着朝霞走出“杂货铺”，用年轻的向上的心勇敢的面对他们今后的生活。<br></p><p>在此谢谢小朋友的推荐！<br></p>
                        </div>
                    </div>
                </div>
                <!--底部文章分类信息和版权-->
                <div class="show-foot">
                    <nuxt-link class="notebook" to="/note/123">
                        <i class="fa fa-book"></i>
                        日记本
                    </nuxt-link>
                    <div class="copyright">
                        © 著作权归作者所有
                    </div>
                </div>
                <!--文章底部的作者信息-->
                <div class="follow-detail">
                    <div class="info">
                        <div class="avatar">
                            <img src="~/assets/img/default-avatar.jpg">
                        </div>
                        <a href="#" class="btn-follow">
                            <i class="fa fa-plus"></i>
                            <span>关注</span>
                        </a>
                        <nuxt-link class="title" to="/u/123">
                            秘名
                        </nuxt-link>
                        <i class="fa fa-mars"></i>
                        <p>
                            写了12886字，被22人关注，获得了 102个喜欢
                        </p>
                    </div>
                </div>
                <!--更多分享-->
                <div class="meta-bottom">
                    <div class="like"  @click="jumped($event)">
                        <div class="like-btn">
                            <a href="">喜欢</a>
                        </div>
                        <div class="like-num">
                            <a href="">50</a>
                        </div>
                    </div>
                    <div class="share">
                        <a  class="share-btn" style="position:relative" @mouseover="qqHandle()" @mouseout="qqHandleout()">
                            <i class="fa fa-qq qq"></i>
                            <pup class="postion-qq"></pup>
                            
                        </a>
                        <a  class="share-btn" v-tooltip="'分享到微博'">
                            <i class="fa fa-weibo weibo"></i>
                        </a>
                        <a  class="share-btn" v-tooltip="'分享到QQ'">
                            <i class="fa fa-weixin weixin"></i>
                        </a>
                        <a  class="share-btn more-share">
                            <v-popover offset="16" >
                            <!-- This will be the popover target (for the events and position) -->
                            <a class="tooltip-target b3" >更多分享</a>
                            
                            <!-- This will be the content of the popover -->
                            <template slot="popover">
                                <ul class="tooltip-ul">
                                    <li><span  class="fa fa-star-half-o" style="color:#01ABEE"></span><span>分享到qq空间</span></li>
                                    <li><span class="fa fa-twitter" style="color:#01ABEE"></span><span>分享到Twitter</span></li>
                                    <li><span class="fa fa-facebook-official" style="color:#4460A1"></span><span>分享到Facebook</span></li>
                                    <li><span  class="fa fa-google-plus" style="color:#569F47"></span><span>分享到Google</span></li>
                                    <li><span class="fa fa-hand-peace-o" style="color:#4460A1"></span><span>分享到豆瓣</span></li>
                                </ul>
                            </template>
                            </v-popover>
                            
                        </a>
                    </div>
                </div>
                  <my-comment></my-comment>
            </div>
        </div>
    </div>
</template>
<script>
    import myComment from '~/components/myComment';
    import myHeader from  '~/components/myHeader';
    import pup from '~/components/pup';
    export default {
        data () {
            return {
                name:'page',
                count:0,
            }
        },
        components:{
            myHeader,
            pup,
            myComment
        },
        methods:{
            jumped(e){
                this.count++;
                console.log(e.target);
                if(this.count%2!=0){
                     e.target.classList.add('jumps');
                     document.querySelector('.like').style.backgroundColor='red';
                }else{
                       e.target.classList.remove('jumps');
                         document.querySelector('.like').style.backgroundColor='white';
                }
            },
          qqHandle:function(){
        document.querySelector('.postion-qq').style.display='block';
        },
          qqHandleout:function(){
          document.querySelector('.postion-qq').style.display='none';
        }
        }

    }
</script>
<style  scoped>
    .postion-qq{
        position: absolute;
        top:-60px;
        display: none;
    };


</style>
