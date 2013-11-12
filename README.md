Keyword Occurrences
=====================

Important Notes:
- This module is only a proof of concept. It is and will not be released in 
drupal.org.
- Do not use this module to crawl sites that you don't own or manage.
- Do not crawl large sites (i.e. yahoo.com) as PHP will potentially run out of
 memory.

Description:
Provides an interface to perform keyword search on a website by accepting two 
parameters (URL and keywords). Once the user input is entered, a table is
rendered with a list of pages (relative paths) and the number of occurrences
of the keywords supplied.

Requirements:
- Libraries 2.x

Installation
- Install the Simple HTML DOM library available at
http://simplehtmldom.sourceforge.net/
on /sites/all/libraries. Make sure the path to the library file
simple_html_dom.php is /sites/all/simplehtmldom/simple_html_dom.php. This module
has been tested with Simple HTML DOM v 1.5.

How to use:
- Go to /keyword-occurrences, provide a URL and keywords, and run the analysis.
