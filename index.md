<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DJX00000Ay5ez',
				'SamsoeMessagingforGitHub',
				'https://samsoe--dev.sandbox.my.site.com/ESWSamsoeMessagingforGitH1744117082164',
				{
					scrt2URL: 'https://samsoe--dev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://samsoe--dev.sandbox.my.site.com/ESWSamsoeMessagingforGitH1744117082164/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'>
</script>

  </body>
</html>
