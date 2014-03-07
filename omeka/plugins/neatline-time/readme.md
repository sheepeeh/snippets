## Embedding Timelines in Omeka Exhibits using iFrames
This method depends on *not* using the default Neatline Timeline pages for display. The iframe CSS could probably be finagled to work with the full page, but it is currently written for timelines of the default size on pages with no  other content.

Copy the **CSS files** to yourtheme/css (or to your existing custom stylesheets)
Be sure to add a queue_css statement for any new css files in header.php

Copy **show.php** to yourtheme/neatline-time/timelines

Paste the code from **exhibit_iframe.html** where you want to embed a timeline, being sure to replace "YOUR TIMELINE URL" with the URL to  your Timeline's page.

You should end up with something like this:
![](https://raw.github.com/sheepeeh/snippets/master/omeka/plugins/neatline-time/timeline-iframe.PNG)
