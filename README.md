#Ti.AmazonDeviceManaging

![](https://developer.amazon.com/public/binaries/content/gallery/headerimage-devicemessaging.png)

##Usage
```javascript

var Adm = require("ti.appwerft.adm");

Adm.isAvailable();

Adm.register();

Ti.App.addEventListener("adm",function(){
});
```

The credentials you set in tiapp.xml

Addiotional we need some modifications in your manifest.xml.