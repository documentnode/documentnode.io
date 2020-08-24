# Version 1.1.109 (beta)

## Security infrastructure for publishing

This week, we developed a security component in the desktop application, as preparation for one-click publishing and other functionalities.

It uses an asymmetric cryptographic algorithm via RSA for authorization and uses SSL to keep the communication between the desktop application and remote hosting services secure.

One-click publishing will make life much easier when we want to update one or more articles on our website after we've made changes in the documents.

You can just use a subdomain provided by us, like `mysite.document.io`, or you can configure a custom domain of your own.

In the future, we will develop features for publishing your content websites to other major platforms, like Github Pages, Amazon S3, Ghost, Wordpress, Medium and so on.

## Miscellaneous improvements & fixes

* Fixed a blank-page issue when running a project located in a network drive
* Fixed display issues of editor tabs when document titles are too long
* Improved the images popup by sorting them by last modified time, and skipping images in output folders
* Improved folder icons by using a different colour to distinguish output folders from regular folders
* Fixed syntax highlight issues for list items
* Improved the auto-creation of list item prefixes
* Improved code block style issues in the preview panel
* Fixed label display issues on exporting dialogues
