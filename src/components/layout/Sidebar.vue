<template>
    <div class="sidebar">
        <div class="home">
            <img src="../../assets/home.svg" alt="">
        </div>
        <div class="back">
            <img src="../../assets/back-arrow.png" alt="">
        </div>
        
    </div>
</template>

<script>
export default {
    name: "Sidebar"
}
</script>

<style scoped>
    .sidebar {
        width: 72px;
        height: 1024px;
        background-color: #ffffff;
        float: left;
        margin-left: 30px
    }
    img {
        height: 20px;
        width: 20px;
        margin: 12px auto;
    }
    .home {
        width: 72px;
        height: 48px;
        background-color: #ececec;
        border-right: 3px #6964d9 solid;
    }
    .back {
        width: 72px;
        height: 48px;
        background-color: #ffffff;
    }
</style>