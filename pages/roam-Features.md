---
title: roam/Features
---

- 

- {{roam/js}}
	 - 
```javascript
var existing = document.getElementById("roamjs-google-calendar");
if (!existing) {
  var extension = document.createElement("script");
  extension.src = "https://roamjs.com/google-calendar.js";
  extension.id = "roamjs-google-calendar";
  extension.async = true;
  extension.type = "text/javascript";
  document.getElementsByTagName("head")[0].appendChild(extension);
}

```

- 
