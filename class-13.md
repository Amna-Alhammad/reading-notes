# ***THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS***
### Persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

### Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

#### - Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
#### - Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
#### - Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

### **What we really want is**

- a lot of storage space
- on the client
- that persists beyond a page refresh
- and isn’t transmitted to the server

## **INTRODUCING HTML5 STORAGE**
### “HTML5 Storage” also known as Web Storage, “Local Storage” or “DOM Storage.”

### HTML5 Storage: it’s a way for web pages to store named key/value pairs locally, within the client web browser.
~~~
      HTML5 STORAGE SUPPORT
IE	FIREFOX	SAFARI	CHROME	OPERA	IPHONE	ANDROID
8.0+	3.5+	4.0+	4.0+	10.5+	2.0+	2.0+
~~~

#### From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.

#### check for HTML5 Storage:
~~~
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
~~~











