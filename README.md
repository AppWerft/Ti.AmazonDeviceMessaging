#Ti.AmazonDeviceManaging


<img src="https://cdn.amazonblogs.com/developer_blog/images/6a0148c71fb71b970c017d3eb4506b970c.png" width=600 />

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