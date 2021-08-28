
<img alt="Night Coding" src="https://giffiles.alphacoders.com/842/8426.gif" width="250px" align="right"/>


You can find and get examples with code source on these repositories 👀

[![facesar](https://img.shields.io/badge/facesar-click%20here-blue?style=for-the-badge&logo=github)](https://facesar.github.io/)

[![python_codes](https://img.shields.io/badge/python_codes-click%20here-blue?style=for-the-badge&logo=python)](https://facesar.github.io/python_codes/)

[![machine-learning](https://img.shields.io/badge/machine_learning-click%20here-blue?style=for-the-badge&logo=python)](https://facesar.github.io/machine-learning-codes/)

[![javascript_codes](https://img.shields.io/badge/javascript_codes-click%20here-blue?style=for-the-badge&logo=javascript)](https://facesar.github.io/roses-javascripts-examples/)

# **PHP**

**_PHP_** is a server scripting language, and a powerful tool for making dynamic and interactive Web pages.

**_PHP_** is a widely-used, free, and efficient alternative to competitors such as Microsoft's ASP.

### **Example**
```sh
<!DOCTYPE html>
<html>
<body>
  
    <?php
    echo "My first PHP script!"; 
    ?>

</body>
</html>
```
# PHP Installation

## What Do I Need?

- Find a web host with PHP and MySQL support
- Install a web server on your own PC, and then install PHP and MySQL


## Use a Web Host With PHP Support
If your server has activated support for PHP you do not need to do anything.

Just create some ```.php``` files, place them in your web directory, and the server will automatically parse them for you.

You do not need to compile anything or install any extra tools.

Because PHP is free, most web hosts offer PHP support.

# PHP Syntax

## Basic PHP Syntax

A **_PHP_** script can be placed anywhere in the document.

A **_PHP_** script starts with ```<?php``` and ends with ```?>:```

<h3 style="color:#C14242">he default file extension for PHP files is <strong style="color:aqua">".php"</strong>.</h3>

### Example
```sh
<!DOCTYPE html>
<html>
<body>
   
    <h1>My first PHP page</h1>

    <?php
    echo "Hello World"; 
    ?>

</body>
</html>
```

## Display Variables

The following example shows how to output text and variables with the <strong style="color:aqua">echo</strong> statement:

```sh
<?php 
$txt1 = "learn PHP";
$txt2 = "facesar.github.io";
$x = 5;
$y = 4;

echo "<h1> .$txt1. </h1>";
echo "Study PHP at " .$txt2. "<br>";
echo $x + $y;
?>
```

The ```print``` statement can be used with or without parentheses: ```print``` or ```print()```.

The following example shows how to output text with the ```print``` command 

### Example
```sh
<?php
print "<h1> php is fun!</h1>";
print "Hello World!<br>";
?>
```