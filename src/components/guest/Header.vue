<script setup lang="ts">

</script>

<template>
    <div class="header container">
        <div class="header_container">
            <a href="#" class="logo"><img src="https://chathamcash.com/wp-content/uploads/2021/01/dummy-logo-5b.png" alt="Vite logo" /></a>
            <div class="nav_links">
                <ul>
                    <li><a href="#">Our story</a></li>
                    <li><a href="#">Membership</a></li>
                    <li><a href="#">Write</a></li>
                    <li><a href="#">Sign In</a></li>
                    <li class="btn"><a href="#" class="button">Get Started</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
.header{
    background: transparent;
    box-sizing: border-box;
    padding: 14px 114px;
    border-bottom: 1px solid #333;
    width: 100%;
}
.header_container{
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.header_container .logo{
    display: inline-block;
    width: 7.4rem;
    line-height: 0;
}
.header_container .logo img{
    width: 100%;
}
.header_container .nav_links ul{
    display: flex;
    align-items: center;
    margin: 0 auto;
}
.header_container .nav_links ul li{
    display: inline-flex;
    align-items: center;
    padding: 4px .8rem;
    list-style: none;
}
.header_container .nav_links ul li a{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-decoration: none;
    color: #333;
    font-size: 14px;
    line-height: 16px;
}
.header_container .nav_links ul li .button{
    color: #fff;
    display: inline-block;
    padding: 0.5rem 1.2rem;
    background: #333;
    border: 1px solid #333;
    font-weight: 400;
    border-radius: 2rem;
    /* min-width: 74px; */
}

@media only screen and (max-width: 760px) {
    .header_container .nav_links ul li{
        display: none;
    }
    .header_container .nav_links ul li.btn{
        display: inline-flex;
        padding: 4px 0;
    }
}
</style>