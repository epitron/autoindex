-------------------------
  AutoIndex for Apache!
=========================

Summary:
  Pretty directory lists for your listless directories!


Installation:

  1) Enable/install PHP.

  2) Checkout the files:

       git clone git://github.com/epitron/autoindex.git

  3) Put the "autoindex" folder on your website so it's accessible via
     "http://yoursite.com/autoindex/"

  4) Edit your Apache config (or .htaccess) and add something like this:

       <Location />
         DirectoryIndex /autoindex/index.php
       </Location>

    ( You can use the "Location" directive to limit what parts of your site
      are autoindexed. Wanna know more? Read up on it here:
      http://httpd.apache.org/docs/2.2/mod/core.html#location )

  5) Profit!

