# How to include wordpress functionality in php pages

<?php
$path = $_SERVER['DOCUMENT_ROOT'];
include_once $path . '/wp-config.php';
include_once $path . '/wp-load.php';
include_once $path . '/wp-includes/wp-db.php';
include_once $path . '/wp-includes/pluggable.php';
// $wpdb is available, do stuff
