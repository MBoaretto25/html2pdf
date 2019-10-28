# Simple HTML to PDF Converter

### installation

1. `pip install -r requirements.txt`

2. wkhtmltopdf
 * For Ubuntu/Debian
 
    `sudo apt-get install wkhtmltopdf`
    
 * For Windows
 
    a. Download [link](https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download/0.12.4/wkhtmltox-0.12.4_msvc2015-win64.exe)
    
    b. Set: PATH variable set binary folder in Environment variables.


### Packing

`python setup.py`

or open terminal as Administrator

`pyinstaller --onefile .\converter.py`

## TODO
 - [ ] Auto Installer
 