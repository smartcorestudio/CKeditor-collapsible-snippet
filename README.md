# CKeditor-collapsible-snippet
This CKeditor plugin creates customizable collapsible text or code blocks using HTML5 details/summary element. Initially it was designed to handle code snippets (like &lt;pre&gt; element), but it can be used with any text, not just code.

##Main features
* Utilizes widget architecture
* Don't require heavy external JS or CSS libraries (for highlighting and so on)
* Easily configurable by end-user (see screenshots below)
* Supports localization
* &lt;strong&gt;, &lt;em&gt; and &lt;a&gt; tags are supported inside text block
* Easy and straightforward installation

##Special notes
This plugin uses:
* HTML5 details/summary tags for implementing spoiler functionality. Current browser support state for this can be found on [http://caniuse.com/#feat=details]
* CKeditor built-in escaping mechanism. If you're not satisfied with it - you can write custom one
* Inline styles for the most of user-defined settings
* Data-attributes for internal storage of user-defined settings

##Help needed!
Unfortunately, sometimes CKEditor don't preserve line breaks. I haven't found any option to make him doing this. If you have any ideas, feel free to create issues and PRs

##Screenshots

![Settings](http://smartcore.ru/images/screenshot-1.png)

![Editor](http://smartcore.ru/images/screenshot-2.png)

![Editor](http://smartcore.ru/images/screenshot-3.png)

##Changing default settings
If you don't like our default settings, you can override it by passing your own settings directly into CKeditor configuration. Example: `{preDefaultTitle: 'Open snippet', preDefaultBordered: true, ...}`

|Setting name|Description|Type|Default value|
|---|---|---|---|
|preDefaultTitle|Title|String|''|
|preDefaultClass|CSS Class|String|''|
|preDefaultMonospace|Monospace font|Boolean|true|
|preDefaultHidesummary|Hide title|Boolean|false|
|preDefaultCollapse|Collapsed|Boolean|false|
|preDefaultWrap|Autowrap long lines|Boolean|false|
|preDefaultBordered|Bordered|Boolean|false|

## License: MIT
