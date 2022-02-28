---
title: roam/js/tagCyc
---

- 
	 - 

	 - 
```javascript
var existing = document.getElementById("roamjs-tag-cycle");
if (!existing) {
  var extension = document.createElement("script");
  extension.src = "https://roamjs.com/tag-cycle.js";
  extension.id = "roamjs-tag-cycle";
  extension.async = true;
  extension.type = "text/javascript";
  document.getElementsByTagName("head")[0].appendChild(extension);
}

```
