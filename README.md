# android-xml-formatter

## Preface
This is a fork of [ByteHamster's android-xml-formatter](https://github.com/ByteHamster/android-xml-formatter) which aims to add functionality for printing to stdout. This will enable editors like Neovim to have formatting capabilities for android xml files using [conform.nvim](https://github.com/stevearc/conform.nvim). 

Formats xml files according to Android Studio's default formatting rules. By default, also re-orders the attributes to specify the `android:id`, `android:layout_width` and `android:layout_height` first. This can be turned off with a command line option.

To view available command line options, execute `java -jar android-xml-formatter.jar --help`.

Can be used as a style check on a CI server by executing and then printing the diff.
