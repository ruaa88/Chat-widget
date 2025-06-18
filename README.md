# Chat-widget<!DOCTYPE html>
<html lang="sr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Premium Chat Widget</title>
</head>
<body>
  <h1>Kontaktirajte nas putem chat-a</h1>

  <!-- PREMIUM.CHAT WIDGET -->
  <div class="pchat-widget-placeholder"></div>
  <script type='text/javascript'>
    (function(d,w,i){
      w.premiumchat = w.premiumchat || [];
      var p = w.premiumchat;
      if(!p.length){
        (() => {
          w.premiumchat_domain = 'https://premium.chat/';
          var s = d.createElement('script');
          s.type = 'text/javascript';
          s.async = true;
          s.src = w.premiumchat_domain + 'embed/js/widget.js';
          var ss = d.getElementsByTagName('script')[0];
          ss.parentNode.insertBefore(s, ss);
        })();
      }
      p.push({'num': p.length, 'wid': i});
    })(document, window, 678913);
  </script>
</body>
</html>
