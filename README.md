# HTMLpuzzle
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pazzle</title>
    <link rel="stylesheet" href="sample.css">
</head>
 <body>
　<div class="wrap">
　　<h1>div pazzle</h1>
    <div class="top blue"></div> <!--hederでも可 -->
    <!-- floatの解除 -->
    <div class="center-wrap">  
      <div class="center-left"></div>
      <div class="center-right"></div>
    </div>  
      
    <div class="bottom"></div>　<!--footerでも可-->
　</div>
 </body>
</html>

css
* {
  margin: 0;
}

    /* クラス指定 */
.blue{
  width:  400px; 
  height: 100px;
  background-color: #141f40;
} 
.center-left{
  width:  150px;
  height: 250px;
  background-color: #80bfa8;
  /* float: left; */
}
.center-right{
  width: 250px;
  height: 250px;
  background-color: #8c2727;
  /* float: left; */
}
.bottom{
  width: 400px;
  height: 100px;
  background-color: #d98d30;

}

.wrap{
  width: 400px;
  margin: 30px auto 0;
}
.center-wrap{
  display: flex;
}
/* .center-wrap::after {
  content: "";
  display: block;
  clear: both;
}  */
/* displayでも横並びにできる */
