# Cookies-in-C-
Cookies in C#

Cookies is a small piece of information stored on the client machine. This file is located on client machines "C:\Document and Settings\Currently_Login user\Cookie" path.  Its is used to store user preference information like Username, Password,City and PhoneNo etc on client machines. We need to import namespace called  Systen.Web.HttpCookie before we use cookie.
 
There are 2 types of Cookies
1. Persistent Cookie - A cookie has not have expired time Which is called as Persist Cookie
2. Non-Persistent Cookie - A cookie has expired time Which is called as Non-Persist Cookie

1.Persistent Cookie-
This types of cookies are permanently stored on user hard drive.Cookies which have an expiry date time are called persistence cookes. This types of cookies stored user hard drive permenently till the date time we set.

2. Non-Persistent Cookie-
This types of cookies are not permanently stored on user hard drive. It stores the information up the user accesng the same browser. When user close the browser the cookies will be automatically deleted.


Cookie's common property
1. Domain => Which is used to associate cookies to domain.
2. Secure  => We can enable secure cookie to set true(HTTPs).
3. Value    => We can manipulate individual cookie.
4. Values  => We can manipulate cookies with key/value pair.
5. Expires => Which is used to set expire date for the cookies.

What are the advantages of Cookies?
1. Its easy to maintain and fast accessble.
2. Cookies are clear text so the user are able to read it.
3. Store user preference information on the client machine.


What are the disadvantages of Cookies?
1. It's not secure.
2. If user clears the cookie information, we will not be able to retrieve it.
3. Each request will have cookie information with page.
