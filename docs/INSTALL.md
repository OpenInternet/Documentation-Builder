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

  * Install wkhtmltopdf with patched qt (see https://wkhtmltopdf.org/downloads.html for additional binaries)

```
wget https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download/0.12.3/wkhtmltox-0.12.3_linux-generic-amd64.tar.xz
tar vxf wkhtmltox-0.12.3_linux-generic-amd64.tar.xz 
cp wkhtmltox/bin/wk* /usr/local/bin/
```

  * Install pandoc

```
sudo apt-get install pandoc
```

  * Install python-setuptools

```
sudo apt-get install python-setuptools
```
