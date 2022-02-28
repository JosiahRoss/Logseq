---
title: roam/js/calendar
---

- 
id:: 93c6cc8e-6ca9-4acb-ad4a-07de8e6130b9
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
id:: b980ddb0-0731-4be6-83f8-9716fde4c688
