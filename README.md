<h1 align="center">
  <br>
  <a href="https://github.com/mkdirlove/WP-Scanner"><img src="https://github.com/mkdirlove/WP-Scanner/blob/main/logo.png" alt="WP-Scanner"></a>
  <br>
  Optimized version of WP_Scanner by GH0STH4CKER.
  <br>
</h1>

#### Installation

Copy-paste this into your terminal:

```sh
git clone https://github.com/mkdirlove/WP-Scanner.git
```
```
cd WP-Scanner
```
```
python3 -m pip install -r requirements.txt
```
```
python3 WP-Scanner.py -h
```
or
```
python3 WP_ScannerV2.py -h
```
#### Usage
``` 
  █ █ █ █▀█   █▀ █▀▀ ▄▀█ █▄ █ █▄ █ █▀▀ █▀█
  ▀▄▀▄▀ █▀▀   ▄█ █▄▄ █▀█ █ ▀█ █ ▀█ ██▄ █▀▄ 
 ------------------------------------------
 [+]  Optimized & Recode by @mkdirlove  [+]
 ------------------------------------------

usage: WP_Scanner.py [-h] [-u URL]

WP-Scanner ~ WordPress Website Scanner Tool

optional arguments:
  -h, --help         show this help message and exit
  -u URL, --url URL  Website Url with https://
```
#### Example Usage
```
python3 WP_Scanner.py -u https://www.jollibee.com.ph
```
#### Example Output
```
  █ █ █ █▀█   █▀ █▀▀ ▄▀█ █▄ █ █▄ █ █▀▀ █▀█
  ▀▄▀▄▀ █▀▀   ▄█ █▄▄ █▀█ █ ▀█ █ ▀█ ██▄ █▀▄ 
 ------------------------------------------
 [+]  Optimized & Recode by @mkdirlove  [+]
 ------------------------------------------


 Website status :  Up

 [+] WordPress Detection :  Yes

 [+] WordPress version  :  5.9

 [+] Webite name         : https://www.jollibee.com.ph

 [+] Webite description  : Jollibee: Food Takeout &amp; Delivery

 [+] Enumerating Plugins : 

 [*]  elementor
 [*]  akismet
 [*]  wp
 [*]  oembed
 [*]  wp-block-editor
 [*]  wp-site-health
 [*]  elementor-pro
 [*]  yoast

 [+] Admin panel found -  https://www.jollibee.com.ph/wp-login.php

 [+] Enumerating usernames : 

 [*] Username Found : jakob-langsethinvestisdigital-com
 [*] Username Found : jfc-admin
 [*] Username Found : ryan-pernackinvestisdigital-com
```

