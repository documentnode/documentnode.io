# Version 1.1.98 (alpha)

## Danish language support

In this version, we added Danish language support to the application. Thanks to Tue Hellstern for helping review the Danish translations.

## Pasting screenshot directly

Added a feature that allows us to paste a screenshot into the text editor directly.

On macOS, use the shortcut `Ctrl+Command+Shift+4` (a portion of the screen) or `Ctrl+Command+Shift+3` (entire screen) to take a screenshot, and then go back to Document Node and press `Command+V`, you will have the screenshot inserted into the document automatically.

It's the same on Windows. Just use a different shortcut `Alt+PrintScreen`.

## Improved website launching performance

When you only have a few documents, everything is fine. But when you have a few hundreds or thousands of documents, you may still want to run a website quickly from Document Node, not wait for processing all the files until you can see a web page.

This week, we have optimised the performance of launching a website from a big documents folder. We tested on a folder with ~800 documents, and each one has about 17000 characters. The website can be launched in 3 seconds.

## Improved document links

In one document, we can link to other documents located in the same project. Just drag and drop one or more documents into the text editor, they will be inserted as document links.

Clicking on a document link on the preview panel will open the target document into a new text editor tab.

Clicking on a document link on the live website will navigate to the corresponding web page.

## Miscellaneous improvements & fixes

* Improved inline code style in preview
* Fixed UI scaling issue on Fedora 29
* Added a shortcut `F2` for renaming files/folders
* Optimised the performance of opening projects with too many files
* Optimised the performance of launching a website from a big project
* Fixed translation issues on the progress bar of launching a website
* Fixed issues of copying text from Document Node and pasting to other applications
* Fixed issues of showing empty pages when starting a web page for a file with special characters in the filename
* Improved DateTime format on blog page by using the locale in preferences

