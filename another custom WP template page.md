note that each custom template page has to have it's unique template name at the
top in order to be able to find and apply it to the "real" wordpress pages

<?php
/*
Template Name: Looper
 */
get_header(); ?>
<div id="primary">
<div id="content" role="main">

<?php 



for ($x = 0; $x <= 10; $x++) {
    echo "The number is: $x <br>";
} 

?>

<?php echo "hello world"; ?>


</div><!-- #content -->
</div><!-- #primary -->

