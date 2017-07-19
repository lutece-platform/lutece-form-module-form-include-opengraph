
#Description

##Introduction

Include open graph tags (aka facebook) in form pages.

Add the following code to page_frameset.html in header
```

						${form_og?default("")}
						Add this meta if needed :
						meta content="YOUR_TYPE" property="og:type"
						meta content="YOUR_SITE_NAME" property="og:site_name"
						meta content="YOUR_LATITUDE" property="og:latitude"
						meta content="YOUR_LONGITUDE" property="og:longitude"
					
```
Add the following code to page_frameset.html in body where you want the facebook button "j'aime"
```

						${form_og_facebook?default("")}
					
```
Add the following code to page_frameset.html in body where you want the google button "+1"
```

						${form_og_google?default("")}
					
```



[Maven documentation and reports](http://dev.lutece.paris.fr/plugins/module-form-include-opengraph/)



 *generated by [xdoc2md](https://github.com/lutece-platform/tools-maven-xdoc2md-plugin) - do not edit directly.*