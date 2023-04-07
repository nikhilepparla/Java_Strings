Java Strings
1)Strings are created in String pool inside Heap area
2)Strings are immutable :
 Which means when ever you create a string with some value and try to change the value it will create new string in string pool
3)creating of strings
 ->String stringName = "String value";
 ->String stringName2 = "String new value";
4)When ever you create a string it will invoke a constructor named "invoke()"
 ->This method will create a new string each time it is called
 ->when you create a string jvm will check the string pool and if the req string is not available in string pool then "invoke()" will be called and new instance is created