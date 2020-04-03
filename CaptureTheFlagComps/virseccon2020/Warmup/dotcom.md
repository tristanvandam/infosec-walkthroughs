# 25 Points

```
DotCom Scavenger Hunt
25

It’s a website scavenger hunt!

Download the file below.

```
- `unzip dotcom_scavenger_hunt.zip`

Cool we get a folder that has a website in it.
When navigating to the local site it has a donate button to paypal. click it, but it navigates to the real paypal.. I notice the token in the paypal url but it changes everytime, so that is a legitimate transaction/payment token for paypal and won't have a flag in it.

Next, i find it weird that there is a robot.txt for a small site, especially one that is hosted locally. I `cat` the file and notihing too interesting. It has the URL to the sitemap, so i download that, but it doesn't have anything interesting in it.  

cool, lets see all the files with `find . -type f`:
```
 f
./css/master.css
./index.html
./js/jquery-1.3.1.min.js
./js/my-jquery.js
./img/layout/light-burst.jpg
./img/layout/favicon.png
./img/layout/icon-alert.png
./img/layout/quote.png
./img/layout/icon-phone.png
./img/layout/dark-burst.jpg
./img/layout/icon-email.png
./img/layout/icon-address.png
./img/content/nothing.png
./img/content/blackbox.png
./img/content/box.png
./robots.txt
./PAY.html
```

Let's write out all files and grep the flag format..
run: `cat * */* | grep -o "LLS{[a-zA-Z0-9_].*}"`
WHoop whoop. the one js file contains the flag:
`LLS{just_find_it_with_grep}`

#Flag
`LLS{just_find_it_with_grep}`