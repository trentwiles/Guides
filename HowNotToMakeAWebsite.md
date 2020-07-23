# How not to make a website

Here are a few simple tips I have learned about making good websites.


## Configuration

### 404/403 Pages

These should never be left as the default! Not only do they look very boring, but they often show the "server signature" which is information about the server a hacker could use to find vulnerabilities. These pages are also written in bare-bones html, so they make your website look a bit, err, quickly made.
<br>
**Bad:**
<br>
![https://riverside.rocks/uploads/aXh0bGVz/404.PNG](https://riverside.rocks/uploads/aXh0bGVz/404.PNG)
<br>
**Good:**
<br>
![https://riverside.rocks/uploads/eW93ZQ==/404-good.PNG](https://riverside.rocks/uploads/eW93ZQ==/404-good.PNG)
<br>

## .htaccess files

These should not allowed to be downloaded. It is the default setting in Apache for these to be forbidden, but always do a check on your website!

## IP

If you self host, it is always a good idea to use a service like Cloudflare to prevent your personal IP from being leaked. Remember, anybody can get the IP of a website my running `ping example.com` (with example.com being your website).
