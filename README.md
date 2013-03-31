Category Aware Walker Nav Menu
==============================

Make Wordpress category menu aware of single page posts.

a) Get code the class from functions.php
b) Set in template:
<?php
  echo wp_nav_menu(array(
    'walker' => new Category_Aware_Walker_Nav_Menu
  ));
?>
