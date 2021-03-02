> ## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS



Initially web applications were always the focus of the development process and there are attempts to make use of cookies
However, problems have always been encountered.

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


what is wanted:

- a lot of storage space
- on the client
- that persists beyond a page refresh
- and isn’t transmitted to the server

HTML5 storage

it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies.

to check if the browser support HTML5 do this code 

`function supports_html5_storage() {`

 `try {`

   ` return 'localStorage' in window && window['localStorage'] !== null;`

 ` } catch (e) {`

  `  return false;`
    
  `}`
`}`


Instead of writing this function yourself, you can use Modernizr to detect support for HTML5 Storage.

`if (Modernizr.localstorage) {`

 `// window.localStorage is available!`

`} else {`

  `// no native support for HTML5 storage :(`

 ` // maybe try dojox.storage or a third-party solution`

`}`



