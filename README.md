# CKeditor-collapsible-snippet
This CKeditor plugin creates customizable collapsible text or code blocks using HTML5 details/summary element. Initially it was designed to handle code snippets (like &lt;pre&gt; element), but it can be used with any text, not just code.

##Main features
- Utilizes widget architecture
- Don't require heavy external JS or CSS libraries (for highlighting and so on)
- Easily configurable by end-user (see screenshots below)
- Supports localization
- &lt;strong&gt;, &lt;em&gt; and &lt;a&gt; tags are supported inside text block

##Special notes
This plugin use:
- HTML5 details/summary tags for implementing spoiler functionality. Current browser support state for this can be found on [http://caniuse.com/#feat=details]
- CKeditor built-in escaping mechanism. If you're not satisfied with it - you can write custom one
- Data-attributes for storing user-defined settings

##Screenshots

![Settings](http://smartcore.ru/images/screenshot-1.png)

![Editor](http://smartcore.ru/images/screenshot-2.png)

## License: MIT
