AJAX Search For Blogger
=============

AJAX search box feature on the blog. AJAX Search Widget for Blogger V2
-------------

![jQuery live search](https://3.bp.blogspot.com/-b6Yb3-Gr6Jk/W8AtGGtADnI/AAAAAAAAHXw/uR89lSUcFhYUm3o2cLbjsI3chLGKxCHmwCLcBGAs/s1600/Cara%2BMenambahkan%2BFitur%2BAjax%2BSearch%2Bdi%2BBlog%2B1.png)

This article is the result of the accumulation of findings - findings I am about how we can use JSON Blogger to create a dynamic search feature simply by using parameters qon a feed link. This feature can be applied to all themes and does not depend on any JavaScript library
![Live search](https://2.bp.blogspot.com/-h3HupKFyOKU/W6GjnzlL_yI/AAAAAAAAJPE/1GcWJo2Clb4WC1mgp0GY1qOH6cKoutMDwCLcBGAs/s1600/blogger-ajax-search-widget.png)
## Widget integration to Blogger
To enable the AJAX search feature on a blog, you don't need to add any HTML markup to the theme, because this widget will use the existing search box as an AJAX search box. All you need to do is add an HTML / JavaScript page element with the content in this code:

``<script src="https://raw.githack.com/soykothasan/AJAX-Search/master/search.min.js?live=true"></script>``

Click *Save Settings* . The AJAX search feature is now ready to use!

---------------------------------------

> If the AJAX search box doesn't work, maybe it's because you added this widget before the search box widget.
> To make it work, you need to put this widget after the search box widget. More can be read [here](https://www.dte.web.id/2013/08/memahami-domcontentloaded.html).

### You can add the parameters above as URL parameters after the file name *search.min.js* :

``html <script src="search.min.js?live=true&amp;chunk=100&amp;text[loading]=Memuat%E2%80%A6"></script>``

- - -
 **Note:** This document is Written by det.web ; you
can [see the source for information '.And' Original Documen][src].

  [src]: https://www.dte.web.id/2018/09/widget-ajax-penelusuran-blogger.html

* * *

