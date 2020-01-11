# BrqErrorHandler
PHP ErrorHandler

[![author](https://img.shields.io/badge/author-brqnet.com-green)](http://brqnet.com/)


-----

![BrqErrorHandler screenshot](https://i.imgur.com/jcNI2YP.png)


**BrqErrorHandler** is an error handler class for PHP. 
provides a pretty
error interface that helps you debug your project.

## Installing

1. Download Or Clone this repo to your project folder.

1. Register the pretty handler in your code:

    ```php
    // hide php errors
    ini_set('display_errors', 0);

    // include BrqErrorHandler
    require_once "BrqErrorHandler/ErrorHandler.php";

    // init
    new BrqErrorHandler;
    ```