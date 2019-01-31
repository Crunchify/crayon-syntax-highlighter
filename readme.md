# Crayon Syntax Highlighter

Supports multiple languages, themes, fonts, highlighting from a URL, local file or post text.

Hi folks - 

On Crunchify.com we are using Crayon Syntax Highlighter Plugin. It's been working perfectly fine without any issue until we upgraded to PHP 7.3 last week.

Site wasn't even loading because of FATAL error:

PHP Fatal error:  Uncaught Error: Call to a member function id() on array in <path>\wp-content\plugins\crayon-syntax-highlighter\crayon_formatter.class.php:36
	
Also, there were around 5 Warning it was throwing. 

PHP Warning:  preg_replace(): Compilation failed: invalid range in character class at offset 4 in G:\w\w\b\wp-content\plugins\crayon-syntax-highlighter\crayon_langs.class.php on line 340

This is our attempt to fix these PHP 7.3 issues. Feel free to download copy and use at your end.

If you want to contribute then feel free to fork repostiroy https://github.com/Crunchify/crayon-syntax-highlighter.

Regards,
App Shah
