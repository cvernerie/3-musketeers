Install
==

Run the following commands :

+ ``git clone git@github.com:cvernerie/3-musketeers.git``
+ ``cd cash`` 
+ ``npm install``   

Usage
== 

This lib allows you to convert an amount from a currency to another by running :  
  
``node bin/index.js <amount> <source-currency> [<target-currencies>...]``

If you don't want to specify the ``target-currency`` each time you run the command, you can save currencies that will be used as **targets by default**, by running :  

``node bin/index.js cash --save [<target-currencies>...]``

Documentation
==

You can open the file `out/index.html` in your browser to display the JSDoc