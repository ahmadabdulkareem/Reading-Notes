# The P,P,F of locl storage for web applications

## Why Store Data on the Client?
The main reason is practicality. JavaScript code running on the browser does not necessarily need to send all information to the server. **There are several use cases:**

* You want to increase performance. You can cache data client-side so it can be retrieved without additional server requests.
* You have a significant quantity of client-side-only data, e.g. HTML strings or widget configuration settings.
* You want to make your application work off-line.

### Cookies:
They can be used for persistent local storage of small amounts of data.
 But they have three potentially *dealbreaking downsides:*

 * Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


## HTML5 Storage 
Web Storage is a new HTML5 API offering important benefits over traditional cookies.

 it’s a way for web pages to store named key/value pairs locally, within the client web browser.

This means you can start using the API’s *sessionStorage* and localStorage objects.
The data can be any type supported by JavaScript.

If you are storing and retrieving anything **other than strings**, you will need to use functions like **parseInt()** or **parseFloat()** to coerce your retrieved data into the expected JavaScript datatype.