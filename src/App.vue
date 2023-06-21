<template>
  <head>
    <link href='https://fonts.googleapis.com/css?family=Noto Sans HK' rel='stylesheet'>
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  </head>
  <body>
    <nav>
      <a href="" class="navtext">Gmail</a>
      <a href="" class="navtext">Images</a>
      <span class="material-icons apps">apps</span>
      <img src="../src/assets/avatar3.png" alt="" class="avatar">
    </nav>
    <div class="main">
        <div class="">
          <img src="../src/assets/googlelogoreal.png" alt="" class="google">
        </div>
        <div class="searchb">
          <span class="material-icons searchicon">search</span>
          <input type="text" value="" placeholder="Search Google or type a URL" required>
          <img src="../src/assets/miclogo.png" alt="" class="mic">
        </div>
        <div class="sbutton">
          <input type="button" name="" value="Google Search">
          <input type="button" name="" value="I'm Feeling Lucky">
          <div class="middle">
      <div id="lang">
        Google offered in:
        <a href="https://www.google.com/setprefs?sig=0_F4LrwAlSfOr-WwEXH_q_ndPt8_8%3D&amp;hl=hi&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwit-JzEvNH_AhXEAogKHZLzD1QQ2ZgBCBE">हिन्दी</a>
        <a href="https://www.google.com/setprefs?sig=0_F4LrwAlSfOr-WwEXH_q_ndPt8_8%3D&amp;hl=bn&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwit-JzEvNH_AhXEAogKHZLzD1QQ2ZgBCBI">বাংলা</a>
        <a href="https://www.google.com/setprefs?sig=0_F4LrwAlSfOr-WwEXH_q_ndPt8_8%3D&amp;hl=te&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwit-JzEvNH_AhXEAogKHZLzD1QQ2ZgBCBM">తెలుగు</a>
        <a href="https://www.google.com/setprefs?sig=0_F4LrwAlSfOr-WwEXH_q_ndPt8_8%3D&amp;hl=mr&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwit-JzEvNH_AhXEAogKHZLzD1QQ2ZgBCBQ">मराठी</a>
        <a href="https://www.google.com/setprefs?sig=0_F4LrwAlSfOr-WwEXH_q_ndPt8_8%3D&amp;hl=kn&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwit-JzEvNH_AhXEAogKHZLzD1QQ2ZgBCBc">ಕನ್ನಡ</a>
        <a href="https://www.google.com/setprefs?sig=0_F4LrwAlSfOr-WwEXH_q_ndPt8_8%3D&amp;hl=ml&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwit-JzEvNH_AhXEAogKHZLzD1QQ2ZgBCBg">മലയാളം</a>
        <a href="https://www.google.com/setprefs?sig=0_F4LrwAlSfOr-WwEXH_q_ndPt8_8%3D&amp;hl=pa&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwit-JzEvNH_AhXEAogKHZLzD1QQ2ZgBCBk">ਪੰਜਾਬੀ</a>
      </div>
        <div class="visua">
          
        </div>
      </div>
    </div>
  </div>
  </body>
</template>
<style scoped>

 body{
        margin: 0;
        padding: 0;
        background: #fff;
      }
      .main{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-100%);
      }
      .google{
        position: relative;
        width: 380px;
        top: 80px;
        left:4pc
      }
    .middle{
      margin-left: -8px;
    display: flex;
    margin-top: 11px;
}
      .searchb{
        width: 500px;
        height: 45px;
        position: absolute;
        transform: translate(-20%,50%);
      }
      input[type="text"]{
        position: absolute;
        width: 100%;
        height: 100%;
        left: 63px;
        margin-top: -23px;
        border-radius: 50px;
        border: 1px solid #d5d4d4;
        outline: none;
        padding: 0 40px 0 45px;
        font-size: 16px;
        font-family: noto sans hk;
        box-shadow: 0 2px 10px -7px #000;
      }
      .searchicon{
        top: -8px;
        left: 74px;
        color: #777;
        font-size: 21px;
        z-index: 1;
        position: absolute;
      }
      .mic{
        position: absolute;
        width: 13px;
        right: -8pc;
        top: -7px;
      }
      .sbutton{
        position: relative;
    top: 66px;
    text-align: center;
    left: 13px;
      }
      input[type="button"]{
        background: #ebe8e8;
        border: none;
        padding: 8px 20px;
        margin: 10px;
        color: #4e4d4d;
        border-radius: 5px;
        outline: none;
      }
      input[type="button"]:hover{
        box-shadow: 0 0 2px #000;
        color: #000;
        background: #ede8e8;
      }
      nav{
        float: right;
        font-family: arial;
        font-size: 13px;
      }
      .avatar{
        width: 35px;
        border-radius: 50%;
        margin: 10px 20px 0 0;
      }
      .navtext{
        color: #444;
        text-decoration: none;
        top: -12px;
        position: relative;
        margin: 5px;
      }
      .navtext:hover{
        text-decoration: underline;
      }
      .apps{
        position: relative;
        margin: 10px;
        top: -6px;
        color: #555;
        cursor: pointer;
      }
      #lang a{
 padding: 0 5px
      }
</style>