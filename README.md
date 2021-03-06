Prompt [![Build Status](https://travis-ci.org/BastienAr/prompt.svg)](https://travis-ci.org/BastienAr/prompt)
======

Prompt a keyboard interactive menu on your cli, and echo the selected option. 

Install
-------

```shell
go get github.com/bastienar/prompt
```

Usage
-----

```shell
prompt Message option1 option2 ...
```
Navigate with <kbd>↑</kbd>, <kbd>↓</kbd>, <kbd>←</kbd>, <kbd>→ </kbd>, <kbd>TAB</kbd>, <kbd>SHIFT</kbd> + <kbd>TAB</kbd>, <kbd>SPACE</kbd>, <kbd>BACKSPACE</kbd>     
Validate or Cancel with <kbd>ENTER</kbd> or <kbd>CTRL</kbd> + <kbd>C</kbd>


Menu is displayed in **Stderr**, selected option to **Stdout**

![screenshot](screenshot.gif)