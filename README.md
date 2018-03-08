# Publishing tools used for OpenInternet Projects

This repository contains the publishing tools to build customized documentation.

[Use the installation instructions found here.](https://github.com/OpenInternet/Documentation-Builder/blob/master/docs/INSTALL.md)


## Common Problems

### Pages are scaled oddly, no page numbers

You are using wkhtmltopdf without a patched qt. Uninstall wkhtmltopdf using apt and install using one of the precompiled binaries: [See the installation instructions.](https://github.com/OpenInternet/Documentation-Builder/blob/master/docs/INSTALL.md)


### Pages are all there, but the text is invisible

An expected font is not available on your system -- review the stylesheet you are using for any named fonts without fallbacks.  Either set fallback fonts or ensure that the font directory in your content respository has the font files.


### The font looks "wrong"

Same as above - the fallback font family is likely working, but the intended font is not available.

### Some content is missing

Starting at the index file you pass to the builder, examine the "include" links to make sure they are pointing at the correct files and are correctly referring to the directory structure / file location in relation to where each index file is located

