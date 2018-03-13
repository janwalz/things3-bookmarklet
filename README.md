## Things 3 bookmarklet

Add a new to-do to your Inbox with one click, using current page title and url.

First, create a new bookmark in your browser, then change the address to: 
```
javascript:location.href='things:///add?title='+document.title+'&notes=URL%3A%20'+document.location.href+'&list=Inbox'
```

------

Based on [Things Link Builder](https://support.culturedcode.com/customer/en/portal/articles/2803573#link-builder), published with [Things 3.4](https://culturedcode.com/things/blog/2018/02/hey-things/)
