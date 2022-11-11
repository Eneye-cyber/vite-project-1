<template>
    <div class="viewport">
        <div class="viewport_container">
            <div class="viewport_text">
                <h1>Stay curious.</h1>
                <p>Discover stories, thinking, and expertise from writers on any topic.</p> 
                <button>Start reading</button>
            </div>
            
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.viewport{
    padding: 14px 114px;
    border-bottom: 1px solid #333;
    width: 100%;
}
.viewport .viewport_container{
    display: flex;
    align-items: center;
    width: 100%;
    min-height: 450px;
}
.viewport .viewport_container .viewport_text{
    max-width: 50%;
}
.viewport .viewport_container .viewport_text h1{
    font-family: 'Times New Roman', Times, serif;
    font-size: 7rem;
    font-weight: 400;
    line-height: 7rem;
    margin: auto;
}
.viewport .viewport_container .viewport_text p{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 1.7rem;
    line-height: 36px;
    margin: 2.4rem 0;
    color: rgba(0, 0, 0, 0.4);
}
.viewport .viewport_container .viewport_text button{
    color: #fff;
    display: inline-block;
    padding: 0.5rem 3rem;
    background: #333;
    border: 1px solid #333;
    font-size: 1.5rem;
    font-weight: 400;
    border-radius: 2rem;
}
</style>