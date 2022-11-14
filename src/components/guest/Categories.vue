<script setup lang="ts">

</script>
<template>
    <div class="categories">
        <div class="categories_container">
            <div class="categories_sub_header">
                <h4>DISCOVER MORE OF WHAT MATTERS TO YOU</h4>
            </div>
            <div class="categories_tags">
                <a href="#" class="tag">Programming</a>
                <a href="#" class="tag">Data Science</a>
                <a href="#" class="tag">Technology</a>
                <a href="#" class="tag">Self Improvement</a>
                <a href="#" class="tag">Writing</a>
                <a href="#" class="tag">Relationships</a>
                <a href="#" class="tag">Design</a>
            </div>

            <div class="categories_footer">
                <ul>
                    <li><a href="#" class="link">Help</a></li>
                    <li><a href="#" class="link">Status</a></li>
                    <li><a href="#" class="link">Writers</a></li>
                    <li><a href="#" class="link">Blogs</a></li>
                    <li><a href="#" class="link">Careers</a></li>
                    <li><a href="#" class="link">Privacy</a></li>
                    <li><a href="#" class="link">Terms</a></li>
                    <li><a href="#" class="link">About</a></li>
                    <li><a href="#" class="link">Text to speech</a></li>
                </ul>
            </div>
        </div>

    </div>
</template>
<style scoped>
.categories{
    width: 100%;
}
.categories .categories_container{
    width: 100%;
}

.categories .categories_container .categories_sub_header{
    width: 100%;
}
.categories .categories_container .categories_sub_header h4{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 0.9rem;
    font-weight: 600;
    line-height: 18px;
    color: rgba(0, 0, 0);
}
.categories .categories_container .categories_text p{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 1rem;
    line-height: 36px;
    margin: 2.4rem 0;
    color: rgba(0, 0, 0, 0.4);
}
.categories .categories_container .categories_tags {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: flex-start;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid rgba(0, 0, 0, 0.1);
}
.categories .categories_container .categories_tags .tag{
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    color: rgba(0, 0, 0, 0.4);
    padding: 6px 15px;
    border: 1px solid rgba(0, 0, 0, 0.1);
    border-radius: 3px;
    margin-right: 8px;
    font-size: 13px;
    margin-bottom: 8px;
}
.categories .categories_container .categories_footer {
    width: 100%;
    padding-top: 1.5rem;
}
.categories .categories_container .categories_footer ul{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    padding: 0;
    margin: 0;
}
.categories .categories_container .categories_footer ul li{
    display: inline-flex;
    align-items: center;
    padding: 0;
    margin-right: 24px;
    margin-bottom: 12px;
    list-style: none;
}

.categories .categories_container .categories_footer ul li .link{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-decoration: none;
    color: rgba(0, 0, 0, 0.4);
    font-size: 13px;
    line-height: 18px;
}

@media only screen and (max-width: 1080px) {
    .categories .categories_container .categories_footer{
        display: none;
    }
    .categories .categories_container .categories_tags {
        border-bottom: 0;
    }
}
</style>