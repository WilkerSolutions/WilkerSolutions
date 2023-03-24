<html>
  <body>
      <script type='text/javascript'>
        function initEmbeddedMessaging() {
          try {
            embeddedservice_bootstrap.settings.language = ''; // For example, enter 'en' or 'en-US'

            embeddedservice_bootstrap.init(
              '00D8A000000P6rv',
              'Miaw',
              'https://sicredi--rafaelago.sandbox.my.site.com/ESWMiaw1679582939243',
              {
                scrt2URL: 'https://sicredi--rafaelago.sandbox.my.salesforce-scrt.com'
              }
            );
          } catch (err) {
            console.error('Error loading Embedded Messaging: ', err);
          }
        };
      </script>
      <script type='text/javascript' src='https://sicredi--rafaelago.sandbox.my.site.com/ESWMiaw1679582939243/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
