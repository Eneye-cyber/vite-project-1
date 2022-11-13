<template>
    <div class="trending">
        <div class="trending_container">
            <div class="trending_sub_header">
                <h4>EXPLORE TRENDING TOPICS</h4>
            </div>
            <div class="trending_posts">
                <div class="post">
                    <div class="post_index">
                        <span>01</span>
                    </div>
                    <div class="post_body">
                        <a href="#" class="post_author"> <div class="img"> <span>A</span></div> Arthur Hayes in Entrepreneur's Handbook</a>
                        <div class="post_topic"><a href="#">Speechless</a></div>
                        <div class="post_date"><p>Nov 9 · 10 min read</p></div>
                    </div>
                </div>
                <div class="post">
                    <div class="post_index">
                        <span>01</span>
                    </div>
                    <div class="post_body">
                        <a href="#" class="post_author"> <div class="img"> <span>A</span></div> Arthur Hayes in Entrepreneur's Handbook</a>
                        <div class="post_topic"><a href="#">Speechless</a></div>
                        <div class="post_date"><p>Nov 9 · 10 min read</p></div>
                    </div>
                </div>
                <div class="post">
                    <div class="post_index">
                        <span>01</span>
                    </div>
                    <div class="post_body">
                        <a href="#" class="post_author"> <div class="img"> <span>A</span></div> Arthur Hayes in Entrepreneur's Handbook</a>
                        <div class="post_topic"><a href="#">Speechless</a></div>
                        <div class="post_date"><p>Nov 9 · 10 min read</p></div>
                    </div>
                </div>
                <div class="post">
                    <div class="post_index">
                        <span>01</span>
                    </div>
                    <div class="post_body">
                        <a href="#" class="post_author"> <div class="img"> <span>A</span></div> Arthur Hayes in Entrepreneur's Handbook</a>
                        <div class="post_topic"><a href="#">Speechless</a></div>
                        <div class="post_date"><p>Nov 9 · 10 min read</p></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.trending{
    padding: 14px 114px;
    border-bottom: 1px solid rgba(0, 0, 0, 0.08);
    width: 100%;
}
.trending .trending_container{
    width: 100%;
}
.trending .trending_container .trending_text p{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 1.7rem;
    line-height: 36px;
    margin: 2.4rem 0;
    color: rgba(0, 0, 0, 0.4);
}
.trending .trending_container .trending_sub_header{
    width: 100%;
}
.trending .trending_container .trending_sub_header h4{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 1rem;
    font-weight: 700;
    line-height: 18px;
    color: rgba(0, 0, 0);
}
.trending .trending_container .trending_posts{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: flex-start;
    widows: 100%;
}
.trending .trending_container .trending_posts .post{
    position: relative;
    flex: 1 0 auto;
    min-width: 376px;
    margin-bottom: 16px;
}
.trending .trending_container .trending_posts .post .post_index{
    position: absolute;
    left:0;
    top:0;
}
.trending .trending_container .trending_posts .post .post_index span{
    color: rgba(0, 0, 0, 0.25);
    font-size: 2rem;
    font-weight: 700;
}
.trending .trending_container .trending_posts .post .post_body{
    padding-left: 50px;
    margin: 4px auto;
}
.trending .trending_container .trending_posts .post .post_body .post_author .img{
   width: 21px;
   height: 21px;
   border-radius: 50%;
   background-color: rgba(0, 0, 0);
   position:relative;
   margin-right: 8px;
}
.trending .trending_container .trending_posts .post .post_body .post_author .img span{
   color: #fff;
   font-weight: 900;
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%,-50%);
}
.trending .trending_container .trending_posts .post .post_body .post_author{
   display: flex;
   width: 100%;
   max-width: 320px;
   color: rgba(0, 0, 0);
   font-size: 0.8rem;
   margin-bottom: 4px;
   text-decoration: none;
}
.trending .trending_container .trending_posts .post .post_body .post_topic{
   width: 100%;
   max-width: 320px;
}
.trending .trending_container .trending_posts .post .post_body .post_topic a{
   color: rgba(0, 0, 0);
   font-size: 1rem;
   font-weight: 700;
   text-decoration: none;
}
.trending .trending_container .trending_posts .post .post_body .post_date p{
   color: rgba(0, 0, 0, o.4);
   font-size: 0.8rem;
   margin: 4px 0;
}
/* .trending .trending_container .trending_text button{
    color: #fff;
    display: inline-block;
    padding: 0.5rem 3rem;
    background: #333;
    border: 1px solid #333;
    font-size: 1.5rem;
    font-weight: 400;
    border-radius: 2rem;
    cursor: pointer;
} */
</style>