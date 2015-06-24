# vti_bookmarklet
========

This repository contains a tiny script for a bookmarklet which will load a virustotal intelligence query for the current basic analysis page.    

## Usage

### Chrome

* Open Bookmark Manager and/or Add Page on bookmark bar
* Enter a Bookmark name
* Paste the javascript into the URL/second field.

```javascript
javascript:void%20function(){(function(){var%20o=window.location,e=/file\/([a-f0-9]+)\//,i=e.exec(o),n=i[1],t=%22https://www.virustotal.com/intelligence/search/%3Fquery=%22+n;document.location.href=t})()}();
```


