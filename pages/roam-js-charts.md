---
title: roam/js/charts
---

- 
	 - 
```javascript
var existing = document.getElementById("roamjs-charts");
if (!existing) {
  var extension = document.createElement("script");
  extension.src = "https://roamjs.com/charts.js";
  extension.id = "roamjs-charts";
  extension.async = true;
  extension.type = "text/javascript";
  document.getElementsByTagName("head")[0].appendChild(extension);
}

```

- 
