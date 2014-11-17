Googl-PHP-Simpleclass
=========================

This class was designed to shorten links in a minimum number of commands.


# Usage for unique link
```
<?php
require_once('class.googl.php');
$googl = new googl("API_KEY");
$googl->link("http://www.google.com/"); 
echo $googl->link;
?>
```

# Usage for multiple links:
```
<?php
require_once('class.googl.php');
$googl = new googl("API_KEY");
$googl->content("Hello World! http://www.google.com/ http://www.yahoo.com/"); 
echo $googl->content;
?>
```

# Usage without API KEY:
```
$googl = new googl();
```
