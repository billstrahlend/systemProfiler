# System Profiler #
**System Profiler** is a project that is setup to provide information on the user's system and browser via client-side script/access. This is done through simple HTML and JavaScript commands.

---

## Scope ##
The *System Profiler* can be used for troubleshooting purposes when a user is experiencing issues when browsing within an online resource/tool.

## How to Use ##
You can send the URL of the *System Profiler* to the user. When they click on the link, the *HTML* page will generate the user's data. At the top of the page a button is provided labeled as *Send Data*. Once the user clicks on this, using the user's email client a new email is created with the user's data in the body of the email. All they need to do is click send.

### Adding Your Email Address ###
You can add your email address to the end of the URL and when the user clicks the *Send Data* button, your email address will populate in the *To* field. To auto-populate your email address, simply add the following to the end of the URL for the tool:

    ?x=youremailaddress@domainprovider.com

*For Example:*
    
    www.yourdomain.com/folderForSystemProfiler/?x=youremailaddress@domainprovider.com

### Global IP Retrieval ###
The only reason you will need to use the SHTML file type is when you are wanting to retrieve the the Global IP address. The Global IP address only provides an IP address of the network that the user is on. This is not an IP to their specific device/system.

## License / Copyright Notice ##
*&copy; Copyright 2012 Bill Strahlend. All rights reserved.*