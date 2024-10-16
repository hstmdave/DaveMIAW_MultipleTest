<html>
	<body>
		<script type='text/javascript'>
		function initEmbeddedMessaging() {
		try {
		embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

		embeddedservice_bootstrap.init(
		'00D020000004kT9',
		'ShiftWizard_Messaging_Dev',
		'https://healthstream--davemiaw.sandbox.my.site.com/ESWShiftWizardMessaging1728593219614',
		{
		scrt2URL: 'https://healthstream--davemiaw.sandbox.my.salesforce-scrt.com'
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
