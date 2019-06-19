# Installation Instructions

Currently we have instructions for installing on Debian-based operating systems such as Ubuntu.

 * Install Prerequisites
	
	* To check Python version, try the following commands. Commands may differ based on Python installation
	```
	py --version
	python --version
	python3 --version
	```
	* For Python 2
	```
	sudo apt-get install git pandoc python-setuptools python-pip
	sudo pip install MarkdownPP
	```
	* For Python 3
	```
	sudo apt-get install git pandoc python3-setuptools python3-pip
	sudo pip install MarkdownPP
	``` 

 * Download the Documentation Builder

 ```
 git clone --recursive https://github.com/OpenInternet/Documentation-Builder.git
 ```

  * Download and install [wkhtmltopdf](http://wkhtmltopdf.org/downloads.html) with patched qt (installing from package repositories does not enable all required features)

 ```
 wget https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download/0.12.4/wkhtmltox-0.12.4_linux-generic-amd64.tar.xz
 tar vxf wkhtmltox-0.12.4_linux-generic-amd64.tar.xz 
 cp wkhtmltox/bin/wk* /usr/local/bin/
 ```
