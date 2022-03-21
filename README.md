# Java-Glassfish-for-VScode
Java .jsp web application &amp; glassfish server built for VScode

Moved from NetBeans to VSCode, useful for creating java web apps in VSCode & using glassfish's server to debug

Launch configuration for VSCode has been modified to automatically run & stop the server while debugging.

**Known Issues:**
- You need a index.jsp for your web app to run. This should be the first page of your web app
In some instances, running your project will result in the browser displaying a 404 error. This is because the server takes some time to load and your file may
load faster than the server. To fix it, refreshing your page should be enough to reload the site working on the server.
