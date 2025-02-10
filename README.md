<!DOCTYPE html>
<html lang="zh-CN">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>网址发布页</title>
      <style>
html, body {

    overflow-x: hidden; /* 禁止水平滚动 */
}

         body {
         font-family: 'Arial', sans-serif;
         background: linear-gradient(to right, #3498db, #8e44ad);
         color: #fff;
         margin: 0;
         min-height: 100vh;
         display: flex;
         flex-direction: column;
         align-items: center;
         padding-top: 88px;
         position: relative; /* 为了悬浮按钮定位 */
         
         }
         .header {
    width: 100%;
    position: fixed;
    top: 0; /* 固定在顶部 */
    left: 0;
    display: flex;
    align-items: center; /* 垂直居中 */
    padding: 15px;
    background: rgba(255, 255, 255, 0.8);
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.3);
    z-index: 1000; /* 确保在其他内容之上 */
         }

         .back-button {
         background: transparent;
         color: #3498db;
         border: none;
         font-size: 2.5em;
         cursor: pointer;
         transition: background 0.3s ease, transform 0.3s ease;
         flex: 0 0 auto; /* 不允许按钮伸展 */
         }
         .back-button:hover {
         background: rgba(255, 255, 255, 0.5);
         transform: scale(1.05);
         }
         .title {
         flex: 1; /* 允许标题区域占满剩余空间 */
         text-align: left; /* 中间对齐 */
         padding-left: 10px;
         font-size: 1.8em;
         color: #3498db;
         text-transform: uppercase;
         margin: 0; /* 去掉默认外边距 */
         letter-spacing: 1px;
         }
         .container {
         width: 100%;
         max-width: 800px; /* 限制最大宽度 */
         margin-top: 20px; /* 留出返回按钮的空间 */
         padding: 20px;
         text-align: center;
         }
         .logo {
         width: 100px; /* 根据需要调整logo的大小 */
         margin: 20px auto;
         }
         .section {
         margin: 20px 0;
         padding: 20px;
         background: rgba(255, 255, 255, 0.1);
         border-radius: 10px;
         box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
         }
         ul {
         list-style-type: none;
         padding: 0;
         }
         li {
         margin: 20px 0;
         font-size: 1.3em;
         }
         a {
         display: block;
         text-decoration: none;
         background: #fff;
         color: #3498db;
         font-size: 1.3em;
         padding: 15px 20px;
         border-radius: 10px;
         transition: background 0.3s ease, transform 0.3s ease;
         box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
         word-wrap: break-word;
         }
         a:hover {
         background: #f1c40f;
         color: #fff;
         transform: scale(1.05);
         }
         h2 {
         font-size: 2em;
         margin-bottom: 10px;
         text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.4);
         }
         footer {
         margin-top: 30px;
         font-size: 1em;
         color: rgba(255, 255, 255, 0.9);
         }
         footer p {
         margin: 10px 0;
         line-height: 1.6;
         }
      </style>
   </head>
   <body>
      <div class="header">
   <a class="back-button" href="/"> < </a>
   <h1 class="title">地址发布页</h1>
</div>

      <div class="container">
         <div class="logo" style="width:75px;height:75px;display: flex;justify-content: center;align-items: center;margin: 0 auto;">
            <svg version="1.2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1024 1024">
               <defs>
                  <filter x="-50%" y="-50%" width="200%" height="200%" id="f1">
                     <feDropShadow dx="0.034899496702500955" dy="-0.9993908270190958" stdDeviation="7.5" flood-color="#f8dd90" flood-opacity=".7"></feDropShadow>
                  </filter>
               </defs>
               <style>
                  .s0 { filter: url(#f1);fill: #f8dd90 } 
                  .s1 { fill: #000731 } 
               </style>
               <g id="circle">
                  <path id="S0" class="s0" d="m512 1009c-275.9 0-499-222.2-499-497 0-274.8 223.1-497 499-497 275.9 0 499 222.2 499 497 0 274.8-223.1 497-499 497z"></path>
                  <path id="S1" class="s1" d="m675.8 469.4c33.3 19.3 33.3 67.4 0 86.7l-277.5 160.2c-33.4 19.2-75-4.8-75-43.3v-320.5c0-38.5 41.6-62.5 75-43.3z"></path>
               </g>
            </svg>
         </div>
         <p>为了避免地址丢失，请记住我们的官方发布页！</p>
         <div style="font-size:18px; text-align:center; margin-bottom:10px; color: #FFF; font-weight: bold;">按 Ctrl + D 可以收藏该地址，不迷路</div>
         <div class="section">
            <h2>通过网址获取</h2>
            <ul>

            </ul>
         </div>
         <div class="section">
            <h2>通过邮箱获取</h2>
            <p>联系我们的官方邮箱，您将收到最新消息。</p>
            <p><a href="/cdn-cgi/l/email-protection#2d5458485e4849445745446d4a404c4441034e4240"><span class="__cf_email__" data-cfemail="fa838f9f899f9e93809293ba9d979b9396d4999597">[email&#160;protected]</span></a></p>
         </div>
         <footer>
            <p><strong>温馨提示:</strong> 如果打不开网址，请更换网络。</p>
            <p>！！！请截图保存此页面！！！</p>
         </footer>
      </div>
   <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script></body>
</html>
