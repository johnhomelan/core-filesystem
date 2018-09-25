Core Filesystem	
=========================

A simple class that extends Symfony's Filesystem class add some extra functionality. 


Features
--------

* Adds a methmod to Filesystem to get the contents of a file.


Example
--------

use HomeLan\Core\Filesystem\Filesystem;

$oFs = new Filesystem();
$sData = $oFs->getContents('file.txt');

