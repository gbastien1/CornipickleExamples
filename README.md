# CornipickleExamples
Files that use Cornipickle to verify web page layouts according to specific given rules.

####Note:
These folders should be put in the same folder as the cornipickle.jar file,
and the server started using the --serve-as command.
######example: 
java -jar cornipickle.jar --serve-as local/
and in the browser, type localhost:10101/local/guidelines/index.html

Cornipickle can be downloaded from here:
http://bitbucket.org/sylvainhalle/cornipickle

##Work in progress

###Guidelines:
Uses Gnome's human interface guidelines which can be found here:
https://developer.gnome.org/hig/stable/ui-elements.html.en

The goal is to be able to express every guideline in the cornichon language from the Cornipickle program in order to, later, automatically verify web page layouts according to these guidelines.


###Webpages:
Using cornichon to detect and highlight bugs in "real" webpages (captured with the mozilla MAFF format).
