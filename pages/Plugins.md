---
title: Plugins
---

- [[roam42]]
	 - 
		 - 
```javascript
var existing = document.getElementById("roamjs-roam42-main");
if (!existing) {
  var extension = document.createElement("script");
  extension.src = "https://roamjs.com/roam42/main.js";
  extension.id = "roamjs-roam42-main";
  extension.async = true;
  extension.type = "text/javascript";
  document.getElementsByTagName("head")[0].appendChild(extension);
}

```

- [[roamjs]]
	 - [[Alert]]
		 - Schedule alerts to appear while working in Roam

		 - Code
			 - {{[[roam/js]]}}
				 - 
```javascript
var existing = document.getElementById("roamjs-alert");
if (!existing) {
  var extension = document.createElement("script");
  extension.src = "https://roamjs.com/alert.js";
  extension.id = "roamjs-alert";
  extension.async = true;
  extension.type = "text/javascript";
  document.getElementsByTagName("head")[0].appendChild(extension);
}

```

		 - 

- 

- 

- 
