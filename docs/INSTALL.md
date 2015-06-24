# Installation Instructions

Currently we have instructions for installing on the Ubuntu operating-system.

### Installation Ubuntu

  * Install git

```
sudo apt-get install git
```

  * Download the Documentation Builder

```
git clone --recursive https://github.com/OpenInternet/Documentation-Builder.git
```

  * Download the binary [wkhtmltopdf](http://wkhtmltopdf.org/downloads.html) application for your system.

  * Install wkhtmltopdf

```
sudo dpkg --install wkhtmltox-[VERSION]_[PLATFORM]-[CPU].deb
```

  * Install wkhtmltopdf's dependencies [xfonts-75dpi]. *dpkg does not automatically pull in dependencies so we use apt-get to install them.*

```
sudo apt-get -f install
```

  * Install pandoc

```
sudo apt-get install pandoc
```

  * Install python-setuptools

```
sudo apt-get install python-setuptools
```
