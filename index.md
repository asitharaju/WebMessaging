<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
	</head>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DD6000000VTQ2',
				'Messaging_for_Web',
				'https://sleepforce--sebuludev6.sandbox.my.site.com/ESWMessagingforWeb1692614913512',
				{
					scrt2URL: 'https://sleepforce--sebuludev6.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://sleepforce--sebuludev6.sandbox.my.site.com/ESWMessagingforWeb1692614913512/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
