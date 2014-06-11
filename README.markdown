## Description

The story:

1. Magnus Rosenbaum wrote the original [phptidy](http://phptidy.berlios.de/) script.
2. Eoin Gallagher modified it so that it conforms to the [WordPress Coding Standards](http://codex.wordpress.org/WordPress_Coding_Standards).
3. I put Eoin's version on github, for convenience.

## Basic usage

```
$ wp-phptidy.php replace some-file.php
```

Complete documentation can be found on the phptidy home page: http://phptidy.berlios.de/

Modified to use spaces and code as below

    class MyClass extends SomeClass
    {
        function __construct($arg1, $arg2)
        {
            // do something
        }
        
        function doJob($arg)
        {
            foreach ($variable as $vari) {
                if ($vari == 1) {
                    // do this
                }
                elseif ($vari == 2) {
                    // do another
                }
                else {
                    // do new
                }
            }
            
            do {
                // this is do loop
            } while ($check);
            
            while ($check) {
                // this is while loop
            }
            
            $array = array('Apple', 'Banana', 'Carrot');
        }
    }