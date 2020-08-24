# Command line

Using the Document Node command-line tools, you will be able to:

1. export your writing projects as websites
1. run your writing projects as websites with live-reload
1. publish the websites of your projects to Document Node hosting

When your projects are running as websites from the command line, it's the same as you run it from the software. Any changes in the text editor will be updated to the sites automatically.

Once you've downloaded the command-line tools and configured in `PATH`, you can run the command below:

```Bash
dn
```

And then the general usage information will be printed:

```
Usage: dn [options] tasks...

Document Node Command Line Tools (dn)
The command line tools for publishing your writing projects.

Options:
  -h, --help                         Displays this help.
  -v, --version                      Displays version information.
  -p, --projectDir <projectDir>      Writing project directory
  -o, --outputDir <outputDir>        Output directory to store exported results
  -f, --exportFormat <exportFormat>  Export format, could be 'site' or 'epub'
  -k, --filesToKeep <filesToKeep>    Files to keep when cleaning output
  -b, --subdomain <subdomain>        Subdomain of the publishing website
  -c, --customDomain <customDomain>  Custom domain of the publishing website
  -r, --siteVersion <siteVersion>    Site version of the publishing website

Arguments:
  tasks...                           One or more tasks to be executed

Available tasks are:
  clean    Clean the exporting output directory
  export   Export a project into a website or an eBook
  run      Run a writing project as a website
  publish  Publish the project website to Document Node hosting
```