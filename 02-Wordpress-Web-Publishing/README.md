# Simple web publishing

### Overview:

We'll learn how to set up our own web sites under UB servers.

### Instructions:

1. Go to the below website.
[https://www.buffalo.edu/ubit/service-guides/web-hosting/creating-a-personal-website/getting-started-with-your-personal-website.html](https://www.buffalo.edu/ubit/service-guides/web-hosting/creating-a-personal-website/getting-started-with-your-personal-website.html)
2. Turn on your personal web page.
3. Access to your Myfiles. Usually it will be your I drive (in some cases it's U drive)
[https://www.buffalo.edu/ubit/service-guides/file-storage-and-sharing/accessing-myfiles-from-anywhere.html](https://www.buffalo.edu/ubit/service-guides/file-storage-and-sharing/accessing-myfiles-from-anywhere.html)
4. Under the Myfiles, you will see a folder named "Public_html".
5. Start an empty Notepad file (Hold Windows button and press "R". Type "notepad")
6. Copy the below code and paste it into the empty Notepad file

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="ko" xml:lang="ko">
  <head>
    <meta http-equiv="content-type" content="application/xhtml+xml; charset=utf-8" />

    <title>YOUR NAME</title>
  </head>
  <!--#include virtual="../_include/header.html"-->
  <body>
        <p>Hello, world! </p>
        <p>My name is YOUR NAME....</p>
      <!-- end #conentbody -->
  </body>
</html>
```
7. You may want to edit the text.
8. Save the file as "gis.html" under the "Public_html" folder.
9. Now, let's visit the file via web.
10. Visit the website below. You need to replace [UBIT_NAME] with your UB id.
http://www.acsu.buffalo.edu/~[UBIT_NAME]/gis.html
11. If you edit the html file in Notepad, then your web browser will show the edit (don't forget refresh).
