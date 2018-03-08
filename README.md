# CiscoHackathon 101

This Github page has API reference  for the most popular Cisco environments like Cisco CMX (location based services), DNA Center, Meraki, Cisco Spark & also Security API for Cisco Umbrella & Firepower.
            Each Technology has following sections:
    		•    Use cases:    Common Projects solved using the API infrastructure in specific Environment
                •    Getting started:    Reference to learn more about the technology
                •    HelloWorld:    20-30mins Hands-on learning modules to learn about API                            
                •    Sandbox:        Reference to Lab environments to code

If you are new to Cisco Devnet & would like to know where to get started – here are some popular use cases:

Quick review: https://learninglabs.cisco.com/tracks/app-dev

1)	#NetDevOps – Networking/Automation -Cisco Programmable infrastructure 
			
			
	1a) Cisco CMX 
				Cisco Connected Mobile Experiences (CMX) is a smart Wi-Fi solution that uses the Cisco wireless infrastructure to detect and locate consumers’ mobile devices. With it, your organization can directly deliver content to smartphones and tablets that’s personalized to your visitors’ preferences and pertinent to their real-time indoor locations.
				
		Cisco CMX is the most popular in Cisco API community since it let us build some cool Location based Apps.. Check out this reference that walks you through the basics on how to incorporate CMX API in Python & Node.js Code & more.. 		https://github.com/geekbleek/CMX_Getting_Started_Code
				
				CMX Use Case 
				•	Location based services, Analytics – WiFi & BLE
				•	Allow for users to check how “crowded” an area (event, line, store, etc) is relative to capacity.
				•	Automate attendance and classroom assignments from mobile device

				Getting Started with Cisco CMX :https://developer.cisco.com/site/cmx-mobility-services/
				Hello World: 
				Signup & Login to developer.cisco.com and then visit following URL
				https://learninglabs.cisco.com/modules/dna-cmx-mse

				Always-on-Sandbox
				CMX : https://devnetsandbox.cisco.com/RM/Diagram/Index/3f3178e9-8c8e-4b9a-9ced-689602d493cb?diagramType=Topology
				* Dashboard: http://cmxlocationsandbox.cisco.com/
				* Username: learning
				* Password: learning
				
				
	1b) Cisco DNA Center 
					DNA Center is an IT automation and assurance platform designed to allow you to move faster at scale, lower cost and reduce risk. Capabilities of Cisco DNA Center are exposed through a REST API allowing you to automate, integrate and innovate.

				DNA Center Use Cases 
					•	Automate daily health reports around network support.
					•	Generate and deliver automated network reporting
					•	Provide different reports for different level users. (e.g. CIO gets basic Red, Yellow, Green health report, and high level SLA stats, director gets opened/closed service requests and mttr stats, manager gets wan availability and average latency reports)

				Getting Started: https://developer.cisco.com/site/dna-center/
				Hello World: 	
				Signup & Login to developer.cisco.com and then visit following URL
					https://developer.cisco.com/docs/dna-center/
			       		https://developer.cisco.com/docs/dna-center/#hello-world

				Always-on-Sandbox
				* https://sandboxdnac.cisco.com/
				* username: devnetuser
				* password: Cisco123!


2)	Cloud Managed IT - with Meraki API
				Cisco Meraki is 100% cloud-managed IT. Meraki product lines are all accessible with a simple easy-to-use dashboard & they are all programmable with API .. Access the information from users on network, Client devices to network infrastructure itself. Explore the API docs on Dashboard for more information.

				Meraki Use cases: Join Meraki community here - https://create.meraki.io/
				•	Add WiFi and Bluetooth real-time location services to your app
				•	Remotely manage your Meraki network with the Dashboard API (#NetDevOps)
				•	Add captive portals or splash pages to your customers workflow
				•	Location based services, Analytics – WiFi & BLE
				•	Allow for users to check how “crowded” an area (event, line, store, etc) is relative to capacity.
				•	Automate attendance and classroom assignments from mobile device


				Getting Started    https://developer.cisco.com/site/meraki/
				Hello World: 
				Signup & Login to developer.cisco.com and then visit following URL
					https://learninglabs.cisco.com/modules/getting-started-with-meraki 
					https://documenter.getpostman.com/view/897512/meraki-dashboard-prov-api/2To9xm

				Always-on-Sandbox
					
				https://devnetsandbox.cisco.com/RM/Diagram/Index/a9487767-deef-4855-b3e3-880e7f39eadc?diagramType=Topology
				Login to "Meraki Devnet Network" dashboard with username "devnetmeraki@cisco.com/ ilovemeraki"
				API Key cc54e1f9520616813f654aab8e0dfc614e33c179
				
				Its recommended to create/use your own account with your email-id.
				If you have any challenges - Ask the event co-ordinator (sakskuma[at]cisco.com) to add your email to the Event Meraki network to test the API 
					

3)	Collaboration – Cisco Spark
				Cisco Spark is a simple, secure collaboration platform where you can get things done from anywhere in the world. Cisco Spark APIs and integrations are key to helping you digitize your business. The self-enabled integrations, bots, and 
				APIs can be easily customized to your existing processes and workstreams.

				Cisco Spark Use Cases
				1)	Create a tool that can be used to manage public announcements in a physical space
				•	Auto add users to spark rooms based on physical presence and opt-in
				•	Allow for report on what messages are going to which users
				•	Allow for broadcast messages to be sent
				•	Allow for broadcast messages to be received.

				2)	Chat bot that can be interrogated by branch managers to query various stats relevant to them.
				•	Allow for querying number of unique visitors for any time period
				•	Apply a natural language processor to allow for more "loose" interactions with the chatbot
				•	Render results graphically and save to a portable file format.
					

				Getting Started: https://developer.ciscospark.com/getting-started.html
				Hello World: 
				Signup & Login to developer.cisco.com and then visit following URL
					https://learninglabs.cisco.com/tracks/collab-cloud
			        Sample Bot -with Dialogflow & Heroku
				  Create Bot in few steps with Dialogflow: https://dialogflow.com/docs/integrations/spark
				  Advanced with heroku: https://miningbusinessdata.com/api-ai-tutorial-getting-started-webhooks-heroku/
					
				Always on Sandbox
				Create your own Cisco account
							https://developer.ciscospark.com/getting-started.html
				API Test-mode
								https://developer.ciscospark.com/endpoint-people-get.html


4)	Security
				
	4a) Cisco Umbrella
						Cisco Umbrella & Investigate API lets us configure the secure cloud & investigate about specific URL/ Hash for security health/ catetgory etc.

			Umbrella Use Cases:
				•	Publish list of sites visited in Cisco Spark room
				•	Create Spark Bot to query Security score/Health / Category of Specific URL – 
				•	Add information from other sites like VirusTotal using the free API in addition to Umbrella/ Investigate API

				Getting Started:	https://docs.umbrella.com/developer/enforcement-api/
							https://docs.umbrella.com/developer/investigate-api/
				Hello World: 	
						https://docs.umbrella.com/developer/investigate-api/coding-examples-1/
						https://github.com/opendns/investigate-examples/blob/master/scripts.py
				
				Always on Sandbox
				Use one of the following Demo API key for testing (valid until March 11)
				API Token
                                	Hackathon API ACCESS TOKEN: 3bb69d0a-ccc7-40b5-a386-48632333e381
					Hackathon API ACCESS TOKEN: 645462aa-7c26-4dd2-bf67-35777b1f3ef2
					Hackathon API ACCESS TOKEN: 7be254dc-9e39-4d06-b729-3578827b20db

	4b) Cisco Firepower
				REST API for accessing Next Generation Firewall policy and object information
				
			Firepower Use cases
				•	query intrusion, discovery, user activity, correlation, connection, vulnerability, and application and URL statistics database tables on a Cisco Firepower Management Center

				Getting Started: https://developer.cisco.com/site/firepower/
				Hello World: 
				Signup & Login to developer.cisco.com and then visit following URL
					https://learninglabs.cisco.com/modules/Firepower
				Sandbox 
				Firepower Rest API Lab can be reserved here - https://devnetsandbox.cisco.com/RM/Topology 


				More Sandboxes can be found here: https://developer.cisco.com/site/sandbox/
				Devnet on GitHub https://github.com/CiscoDevNet
				Learning tracks: https://learninglabs.cisco.com/tracks

