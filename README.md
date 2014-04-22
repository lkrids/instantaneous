Instantaneous - a bookmarklet
=============

### Usage
Any time you are on a page that isn't loading quickly enough just tap the Instantaneous bookmarklet.  The bookmarklet proxies the page through a Google service that is designed to pull only the necessary content.  That means no javascript, images, ajax, etc.  Just HTML text.  This is simliar to Instapaper or Pocket except there is no sign up.

This is a perfect example of a site that could benefit from this bookmarklet: http://www.webpagetest.org/result/140418_K0_A18/1/details/

### Installation

1. Copy this code:
```
javascript:void((function(w){w.location="http://www.google.com/gwt/x?u="+encodeURIComponent(w.location)+"&noimg=1";}(window)));
```

2. Bookmark this page
3. Edit the bookmark you created in step 2
4. Update the bookmark's url to be the code copied in step 1

### How it works
After clicking the bookmarklet, you are sent to a Google service that will display only the important content from the page you were on when you clicked the bookmarklet.
