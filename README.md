MultiSelectSpinner
==================

A spinner control for Android that supports multiple selection.

![MultiSelectSpinner dropped][1] &nbsp; ![MultiSelectSpinner closed][2]

Usage:

```java
String[] strings = { "Red", "Blue", "Green" };

MultiSelectSpinner mySpin = (MultiSelectSpinner)findViewById(R.id.my_spin);
mySpin.setItems(strings);

// ...

List<String> selected = mySpin.getSelectedStrings();
```


[1]: https://codethis.files.wordpress.com/2012/06/mss_dropped1.png
[2]: https://codethis.files.wordpress.com/2012/06/mss_closed1.png