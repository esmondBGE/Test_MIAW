<html>
	TEST MIAW Version 2. 
	Iteration 3. 
	09/08/2024
  	<body>
		<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Access_Token" : "asas", "Origin_Page" : "/home/my-accounts", "Session_Token" : "87e10251-3892-4add-8fce-c1af9aed77b3" });
			});
			embeddedservice_bootstrap.init(
				'00DJW000000q7pX',
				'MIAW_Chatbot_Github',
				'https://bordgaisenergyeandu--test.sandbox.my.site.com/ESWMIAWChatbotGithub1713263622188',
				{
					scrt2URL: 'https://bordgaisenergyeandu--test.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
		</script>
		<script type='text/javascript' src='https://bordgaisenergyeandu--test.sandbox.my.site.com/ESWMIAWChatbotGithub1713263622188/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
	 </body>  
</html>
