<template>
    <div class="profile__container">
        <h2>Profile</h2>
        <div>
            <img src="../assets/tanukisan.png" class="profile__icon">
            <p class="profile__text">
                はじめまして。飯島雄一郎と申します。<br>
                2017年4月から社会人になり、社会人になってから今に至るまでずっとIT業界で働いております。<br>
                現在は、Webフロントエンジニアとして働いてます。<br>
                近頃はコーディングのスピードをあげられるよう、とにかくコード書くようにしてます!!
            </p>
        </div>
    </div>
    
</template>

<style scoped>
.profile__container {
    display: block;
    margin: 10px;
    width: 60%;
    height: 500px;
    margin-left: auto;
    margin-right: auto;
    background: #c0c0c0;
}

h2 {
    text-align: center;
}

.profile__icon {
    margin: 25px;
    float: left;
    border-radius: 50%;
}

.profile__text {
    margin-top: 150px;
    float: left;
}
</style>