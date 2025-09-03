<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Spa Nga Henry</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
      color: #333;
    }
    header {
      background-color: #f8cdd2;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 30px;
      gap: 20px;
    }
    .service {
      background-color: #fff0f3;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      width: 300px;
      text-align: center;
      padding: 20px;
    }
    .service img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }
    .service h3 {
      margin-top: 15px;
      font-size: 1.2em;
    }
    footer {
      background-color: #f8cdd2;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Spa Nga Henry</h1>
    <p>Thư giãn - Làm đẹp - Tái tạo năng lượng</p>
  </header>

  <section class="services">
    <!-- Dịch vụ chăm sóc -->
    <div class="service">
      <img src="https://bestme.vn/images/blogs/2023/09/24/cham-soc-da-mat-tai-spa.jpg" alt="Massage Body">
      <h3>Massage Body</h3>
      <p>Giúp thư giãn cơ thể, giảm stress và cải thiện tuần hoàn máu.</p>
    </div>
    <div class="service">
      <img src="https://bestme.vn/images/blogs/2023/09/24/dap-mat-na-cham-soc-da.jpg" alt="Chăm sóc da mặt">
      <h3>Chăm Sóc Da Mặt</h3>
      <p>Làm sạch sâu, cấp ẩm và phục hồi làn da khỏe mạnh.</p>
    </div>
    <div class="service">
      <img src="https://bestme.vn/images/blogs/2023/09/24/triet-long-body.jpg" alt="Triệt lông">
      <h3>Triệt Lông Công Nghệ Cao</h3>
      <p>Giải pháp triệt lông an toàn, hiệu quả và lâu dài.</p>
    </div>

    <!-- Dịch vụ phun xăm thẩm mỹ -->
    <div class="service">
      <img src="https://xaydungso.vn/images/phun-may-dep.jpg" alt="Phun mày tản bấm">
      <h3>Phun Mày Tản Bấm</h3>
      <p>Giúp định hình chân mày tự nhiên, hài hòa với khuôn mặt.</p>
    </div>
    <div class="service">
      <img src="https://xaydungso.vn/images/phun-moi-collagen.jpg" alt="Phun môi collagen">
      <h3>Phun Môi Collagen</h3>
      <p>Cho đôi môi căng mọng, hồng hào và đều màu tự nhiên.</p>
    </div>
    <div class="service">
      <img src="https://xaydungso.vn/images/phun-mi-mat.jpg" alt="Phun mí mắt">
      <h3>Phun Mí Mắt</h3>
      <p>Tạo đường mí sắc nét, giúp đôi mắt thêm cuốn hút mà không cần trang điểm.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Spa Nga Henry. All rights reserved.
  </footer>

  <!-- Start of LiveChat (www.livechat.com) code -->
  <script>
    window.__lc = window.__lc || {};
    window.__lc.license = 19289378;
    window.__lc.integration_name = "manual_onboarding";
    window.__lc.product_name = "livechat";
    ;(function(n,t,c){
      function i(n){return e._h?e._h.apply(null,n):e._q.push(n)}
      var e={_q:[],_h:null,_v:"2.0",
        on:function(){i(["on",c.call(arguments)])},
        once:function(){i(["once",c.call(arguments)])},
        off:function(){i(["off",c.call(arguments)])},
        get:function(){if(!e._h)throw new Error("[LiveChatWidget] You can't use getters before load.");return i(["get",c.call(arguments)])},
        call:function(){i(["call",c.call(arguments)])},
        init:function(){
          var n=t.createElement("script");
          n.async=!0;
          n.type="text/javascript";
          n.src="https://cdn.livechatinc.com/tracking.js";
          t.head.appendChild(n)
        }
      };
      !n.__lc.asyncInit && e.init();
      n.LiveChatWidget = n.LiveChatWidget || e
    }(window,document,[].slice))
  </script>
  <noscript>
    <a href="https://www.livechat.com/chat-with/19289378/" rel="nofollow">Chat với chúng tôi</a>, powered by
    <a href="https://www.livechat.com/?welcome" rel="noopener nofollow" target="_blank">LiveChat</a>
  </noscript>
  <!-- End of LiveChat code -->

</body>
</html>
