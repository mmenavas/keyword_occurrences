Keyword Occurrences
=====================

### Important Notes:
- This module is only a proof of concept.
- Do not use this module to crawl sites that you don't own or manage.
- Do not crawl large sites (i.e. yahoo.com) as PHP will potentially run out of
 memory.

### Description:
This module provides an interface to perform keyword search on a website by accepting two 
parameters (URL and keywords). Once the user input is entered, a table is
rendered with a list of pages (relative paths) and the number of occurrences
of the keywords supplied.

### Requirements:
- Libraries 2.x

### Installation:
- Download the Simple HTML DOM library from http://simplehtmldom.sourceforge.net/ and place
it on your site's libraries directory (`/sites/all/libraries`). Make sure the path to the library file
simple_html_dom.php is `/sites/all/libraries/simplehtmldom/simple_html_dom.php`. This module
has been tested with Simple HTML DOM v 1.5.

### How to use:
- Install and enable this module on your drupal site.
- Navigate to `/keyword-occurrences`, fill out the keyword analysis form, and submit form.

### Troubleshooting:
- Make sure `simple_html_dom.php` is in correct directory. Refer to Installation section in this document.
- Make sure `simple_html_dom.php` has read permission for owner, group and everybody (444).
- Clear drupal caches after modifying `simple_html_dom.php`'s file permissions.
