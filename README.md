# Cloud Attack                                                       
                                                          

It is a simply script with a library to bypass Cloudflare UAN anti-ddos page, build in js.

[![js-semistandard-style](https://cdn.rawgit.com/flet/semistandard/master/badge.svg)](https://github.com/Flet/semistandard)

[![Build status](https://img.shields.io/travis/codemanki/cloudscraper/master.svg?style=flat-square)](https://travis-ci.org/codemanki/cloudscraper)
[![Coverage](https://img.shields.io/coveralls/codemanki/cloudscraper.svg?style=flat-square)](https://coveralls.io/r/codemanki/cloudscraper)
[![Dependency Status](https://img.shields.io/david/codemanki/cloudscraper.svg?style=flat-square)](https://david-dm.org/codemanki/cloudscraper)
[![Greenkeeper badge](https://badges.greenkeeper.io/codemanki/cloudscraper.svg?style=flat-square)](https://greenkeeper.io/)

This library is a port of python module cloudflare-scrape with couple enhancements and test cases ;)
. All grats to its author \m/

If the page you want to access is protected by Cloudflare, it will return special page, which expects client to support Javascript to solve challenge.

This small library encapsulates logic which extracts challenge, solves it, submits and returns the request page body.

You can use cloudscraper even if you are not sure if Cloudflare protection is turned on.

In general, Cloudflare has 4 types of _common_ anti-bot pages:
  - Simple html+javascript page with challenge
  - Page which redirects to original site
  - Page with recaptcha
  - Page with error ( your ip was banned, etc)
  

Usage
============
```javascript
Install on Kali/Debian <a href="https://colab.research.google.com">here</a>

!git clone https://github.com/CryptoXSS/cloudAttack3
%cd cloudAttack3
!chmod +x install.sh
!./install.sh

Run: node cloudattack.js --attack "yoursite" --threads 500 
Proxys: --proxy true --updateproxy true


Example: !node cloudattack.js --attack "https://www.acloudflaresite.com" --threads 1000 --proxy true   
```

#Update proxy.txt
https://1drv.ms/u/s!AoFeNfGwTmEFiHUT3F2aoCMH4_Dl?e=myTUfg

## Dependencias:
  - npm install 
  - npm install minimist 
  - npm install cloudscraper
  

## Our contributors 
 - [D-Code](https://github.com/dcodeni)
 - [Azmyoel](https://github.com/azmyoel)
 - [YottaiQ](https://github.com/yottaiq)
 

Version 1.0

Twitter: @AnonGuegue
 
