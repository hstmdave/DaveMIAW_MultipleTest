<html>
  <body>
    <script type='text/javascript'>
      function initEmbeddedMessaging() {
        try {
          embeddedservice_bootstrap.settings.language = 'en_US'; // Set language preference
          
          embeddedservice_bootstrap.init(
            '00D020000004kT9', // Salesforce Org ID
            'ShiftWizard_Messaging_Dev', // Embedded Service Deployment Name
            'https://healthstream--davemiaw.sandbox.my.site.com/ESWShiftWizardMessaging1728593219614', // Embedded Service Site URL
            {
              scrt2URL: 'https://healthstream--davemiaw.sandbox.my.salesforce-scrt.com' // SCRT URL
            }
          );
        } catch (err) {
          console.error('Error loading Embedded Messaging: ', err);
        }
      };
    </script>
    <script type='text/javascript' src='https://healthstream--davemiaw.sandbox.my.site.com/ESWShiftWizardMessaging1728593219614/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
