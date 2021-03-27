<template>
  <div class="profile">
    <h1>Profile</h1>
    <h3>プロフィール</h3>
    <br><br>
    <div class="profile__left">
      <img src="~/assets/img/face.png" class="face" alt="顔写真">
    </div>
    <div class="profile__right">
    <ul>
      <li>名前：加本 真大（かもと まさひろ）</li>
      <li>生年月日：1997年11月30日（23歳）</li>
    </ul>
    <ul class="icons">
      <li>
        <a
          href="https://twitter.com/rnasahiro"
          target="_blank"
          rel="noopener noreferrer"
          ><img class="icon" src="~/assets/img/twitter.png" alt="twitter"
        /></a>
      </li>
      <li>
        <a
          href="https://qiita.com/masahiroz5"
          target="_blank"
          rel="noopener noreferrer"
          ><img class="icon" src="~/assets/img/qiita.png" alt="qiita"
        /></a>
      </li>
      <li>
        <a
          href="https://github.com/masahiroz5"
          target="_blank"
          rel="noopener noreferrer"
          ><img class="icon" src="~/assets/img/github.png" alt="github"
        /></a>
      </li>
      <li>
        <a
          href="https://mail.google.com/mail/?view=cm&to=l.veg4sz5gmail.com"
          target="_blank"
          rel="noopener noreferrer"
          ><img class="icon" src="~/assets/img/gmail.png" alt="gmail"
        /></a>
      </li>
    </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.face{
  width: 300px;
  height: auto;
}
.profile__left{
  float: left;
  margin-left: 200px;
}
.profile__right{
  float: right;
  margin-right: 250px;
}

.icon{
  width: 50px;
  height: auto;
  margin-left: 15px;
}
.icons{
  display: flex;
  justify-content: center;
}
li{
 list-style: none;
}
a:hover{
  opacity: 0.8;
}
</style>