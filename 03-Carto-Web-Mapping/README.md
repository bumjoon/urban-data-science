# Simple web mapping with Carto

### Overview:

Today we'll learn how to create simple (yet attractive and interactive) web maps with Carto.com to visualize spatial data on the web.
This will be a primarily self-directed study using the official Carto lessons. You will publish the John Snow Cholera map.

### Readings:

Take an overview of Carto Builder [overview](https://carto.com/builder/)

### Class Session:

1. Sign up for a [Carto](https://carto.com/signup/) account
2. Instructor demo
2. Go to the [Carto Guides](https://carto.com/learn/guides) and complete the "Intro" courses (in total they make take ~ 1 hr)
3. Download the cholera map data and make your own map
4. Publish your map on your personal UB website [Instructor Demo](http://www.acsu.buffalo.edu/~bumjoonk/gis.html)

### Exercise:

1. The first step for this exercise will be to complete the "Intro" courses (~1 hour) in [Carto Guides](https://carto.com/learn/guides). You don't need to submit anything from the courses. 
2. If you find the courses interesting, you may want to navigate other courses.
3. Next, download the cholera dataset over here, [Data](http://blog.rtwilson.com/updated-snow-gis-data/) and unzip the file.
4. We are now going to upload two datasets from the John Snow data directory. 
  The first is all the pumps in the neighborhood. 
  The second is all the deaths reported due to cholera in the neigborhood. 
  
  When you upload shapefiles, you need to be sure to upload all associated files at once, this can be done by creating a __ZIP__ that contains each of them. So, for the pumps, create a zipfile containing each of the following,

* Pumps.shp
* Pumps.prj
* Pumps.sbx
* Pumps.shx
* Pumps.dbf

  Select them and create a new zip, call it something easy, Pumps.zip for example. Now, we will do the same with the cholera deaths. Select and create a zip of the following files,

* Cholera_Deaths.shp
* Cholera_Deaths.prj
* Cholera_Deaths.sbx
* Cholera_Deaths.shx
* Cholera_Deaths.dbf
* Cholera_Deaths.sbn

  Again, call it something simple, like Cholera.zip for example. Now, start by dragging our Pumps.zip file to your dashboard. You should end up with a table simply called, pumps. Next, go back to your dashboard by clicking the Carto logo at the upper left of the screen. Now, drag your Cholera.zip file to your dashboard. Great! You should now have a table called cholera_deaths.

5. Using your uploaded data set(s), create at least one map with Carto, showing the associations between pumps and Cholera deaths. Adhere to the best practices you have learned from the tutorials – including thoughtful use of colors, data, and labels.

6. You should have a html file under `I:/public_html` (this is your personal UB webpage folder), which was activated in a previous lab.
  If you haven't activated your personal website, visit [this website](https://www.buffalo.edu/ubit/service-guides/web-hosting/creating-a-personal-website/getting-started-with-your-personal-website.html).
  If the website is activated and you don't have a html file under `I:/public_html`, create one with Notepad software. Save the file as `gis.html`.

~~~~ 
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <meta http-equiv="content-type" content="application/xhtml+xml; charset=utf-8" />

    <title>[YOUR NAME]</title>
  </head>
    <body>
        <p>URP 569</p>
        <p>This is [YOUR NAME]'s John Snow Cholera Map</p>

        [insert the iframe here]
        
        <p>[insert your discussions here]</p>
  </body>
</html>
~~~~

  Again, visit the instructor's [demo webpage](http://www.acsu.buffalo.edu/~bumjoonk/gis.html) on Google Chrome. Hold CONTROL and press "U" key. Then you can see its [source view](view-source:http://www.acsu.buffalo.edu/~bumjoonk/gis.html).

7. Now, you should have a public webpage at this url address 'http://www.acsu.buffalo.edu/~[UBID]/gis.html' (Note: [UBID] should be your UBIT ID). Open an internet brower like Google Chrome. Copy and paste your url address.
8. In the above webpage, include a write-up discussing at a minimum the following elements:
   1. Where is the data from and how did you acquire it?
   2. What is the data about and why is it interesting?
   3. What stories do your maps tell?
  You may use [basic html code](https://www.tutorialspoint.com/html/html_basic_tags.htm) to format your discussions.   
9. Submit a document showing your webpage link on UBLearns.
