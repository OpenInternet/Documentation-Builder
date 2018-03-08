# Installation Instructions

Currently we have instructions for installing on the Ubuntu operating-system.

 * Install Prerequisites

```
sudo apt-get install git pandoc python-setuptools
```

 * Download the Documentation Builder

```
git clone --recursive https://github.com/OpenInternet/Documentation-Builder.git
```

  * Download and install [wkhtmltopdf](http://wkhtmltopdf.org/downloads.html) with patched qt:

```
wget https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download/0.12.4/wkhtmltox-0.12.4_linux-generic-amd64.tar.xz
tar vxf wkhtmltox-0.12.4_linux-generic-amd64.tar.xz 
cp wkhtmltox/bin/wk* /usr/local/bin/
```
