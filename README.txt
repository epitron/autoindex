-------------------------
  AutoIndex for Apache!
=========================

Summary:
  Pretty directory lists for your listless directories!


Installation:

  1) Enable/install PHP.

  2) Put the "autoindex" folder on your website so it's accessible via
     "http://yoursite.com/autoindex/"

  3) Edit your Apache config (or .htaccess) and add something like this:

       <Location />
         DirectoryIndex /autoindex/index.php
       </Location>

     (Location directive can limit where autoindexes are enabled.
      Read up!)

  4) Profit!

