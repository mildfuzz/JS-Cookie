Cookie
======

cookie javascript library


Usage
-----

`value = cookie.get(name);`

*name* - cookie name

return cookie value or null if not set


`cookie.set(name, value, expires, path, domain, secure);`

*name* - cookie name

*value* - string value

*expires* - days before expire. If omitted, the cookie will expire at the end of the session (when the browser closes). 

*path* - The path on the server in which the cookie will be available on. The default value is the current directory that the cookie is being set in. 

*domain* - The domain that the cookie is available to. Cookies available to a lower domain, such as 'example.com' will be available to higher subdomains, such as 'www.example.com'.

*secure* - Indicates that the cookie should only be transmitted over a secure HTTPS connection from the client. Default is false.


`cookie.remove(name);`

*name* - cookie name


`cookie.isEnabled();`

true or false
