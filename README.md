
Use xray +caddy to deploy protocols such as vmess vless trojan shadowsocks socks transmitted via ws at the same time, and the camouflage website has been configured by default.
Support tor network, and you can start xray and caddy through a custom network configuration file to configure various functions on demand
Supports storage of custom files. Both directories and account passwords are UUID. The client must use TLS to connect to
Heroku. It provides us with a free container service. We should not abuse it, so this project should not be used as a long-term circumvention.
Mirror image
This image will not be blocked because it takes up a lot of resources. After registering a Heroku account and logging in, click the button below to deploy.

### Server

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/bodsoe/food) 

Click on the purple above `Deploy to Heroku` jump to the heroku app creation page, fill in the name of the app, select the node (European node is recommended, and the US node will automatically delete YouTube comments and likes!), modify some parameters and UUIDs as needed, and click below deployStart to create the deployment application.
If an error occurs, you can try a few more times. After the deployment is completed, the bottom of the page will be displayed `Your app was successfully deployed`

* Click Manage App to view and reset the parameters in the Config Vars item under Settings
* Click Open app to jump to the welcome page domain name to assign a domain name to heroku, the format is xxx.herokuapp.comfor client
* The default protocol password is 24b4b1e1-7a89-45f6-858c-242cf53b5bdb, the WS path is $UUID-[vmess|vless|trojan|ss|socks] format