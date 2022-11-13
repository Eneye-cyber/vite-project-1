<template>
    <div class="articles">
        <div class="articles_container">
            
            <div class="post">
                <div class="post_body">
                    <a href="#" class="post_author"> <div class="img"> <span>A</span></div> Arthur Hayes in Entrepreneur's Handbook</a>
                    <div class="post_topic"><a href="#">Middle Seat x John Fetterman: Flipping a U.S. Senate Seat from Red to Blue</a></div>
                    <div class="post_topic"><p>How the instincts that drive product development start much earlier than we might think</p></div>
                    <div class="post_date"><p>Nov 9 · 10 min read</p></div>
                </div>
                <div class="post_image">
                    <div></div>
                    <!-- <img src="" alt=""> -->
                </div>
            </div>
            
            
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.articles{
    padding: 14px 0;
    width: 100%;
}
.articles .articles_container{
    width: 100%;
}
.articles .articles_container .post{
    position: relative;
    width: 100%;
    display: flex;
    justify-content: space-between;
    min-width: 376px;
    margin-bottom: 16px;
    padding-right: 30px;
}
.articles .articles_container .post .post_image{
    flex: 1 0 40%;
    margin: 4px auto;
}
.articles .articles_container .post .post_image div{
    width: 200px;
    height: 136px;
    max-width: 80%;
    border-radius: 12px;
    background-color: burlywood;
    margin: 0 auto;
}
.articles .articles_container .post .post_body{
    flex: 1 0 60%;
    margin: 4px auto;
}
.articles .articles_container  .post .post_body .post_author .img{
   width: 21px;
   height: 21px;
   border-radius: 50%;
   background-color: rgba(0, 0, 0);
   position:relative;
   margin-right: 8px;
}
.articles .articles_container  .post .post_body .post_author .img span{
   color: #fff;
   font-weight: 900;
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%,-50%);
}
.articles .articles_container  .post .post_body .post_author{
   display: flex;
   width: 100%;
   color: rgba(0, 0, 0);
   font-size: 0.8rem;
   margin-bottom: 12px;
   text-decoration: none;
}
.articles .articles_container  .post .post_body .post_topic{
   width: 100%;
   padding-right: 12px;
}
.articles .articles_container  .post .post_body .post_topic a{
   color: rgba(0, 0, 0);
   font-size: 1.4rem;
   font-weight: 700;
   text-decoration: none;
}
.articles .articles_container  .post .post_body .post_topic p{
   color: rgba(0, 0, 0, 0.45);
   font-size: 18px;
   line-height: 20px;
   margin: 12px 0!important;
}
.articles .articles_container  .post .post_body .post_date p{
   color: rgba(0, 0, 0, 0.6);
   font-size: 0.8rem;
   margin: 4px 0;
}
</style>