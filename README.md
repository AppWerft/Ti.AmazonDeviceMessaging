#Ti.AmazonDeviceManaging
![](https://developer.amazon.com/public/binaries/content/gallery/headerimage-devicemessaging.png)

##Usage
```javascript

var Adm = require("ti.appwerft.adm");

if (Adm.isAvailable()==true) {
	if (Adm.getRegistrationId() == null) {
    	startRegister();
    }	
  	Ti.App.addEventListener("ADM_onRegistered",function(){
	});
	Ti.App.addEventListener("ADM_onUnRegistered",function(){
	});
	Ti.App.addEventListener("ADM_onRegistrationError",function(){
	});
	Ti.App.addEventListener("ADM_onMessage",function(){
	});
}	
```

The credentials you set in tiapp.xml

Addiotional we need some modifications in your manifest.xml.