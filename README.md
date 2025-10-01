## Translations for Flood and Tower Defense

You can make a new translations by copying the english version `bundle.properties` and renaming 
the new bundle to `bundle_(your locale).properties`.
Languages locales can be found [here](https://www.science.co.il/language/Locale-codes.php).

When translating, please do not touch the following:
- {0} - formatting indexes (moving them is fine if necessary)
-  - icons
- <Flood> - tags
- [accent] - colors (you can consult with io developers if you think a change/removal would benefit the readability)
- \n - newlines and backslashes at the end of the strings

You shouldn't translate the following proper nouns:
- **Flood**
- **FloodCompat**

Please also make sure that your text editor uses UTF8/16 encoding.
[Visual Studio Code](https://code.visualstudio.com/) is known to have few to no issues with it.