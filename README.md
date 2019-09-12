# HexPass

**Note: this project has not been implemented though may serve as a future area of research**

此程式碼的範圍：利用網站用戶的個人資料來透過深度學習猜出帳號密碼

## 組員
韓哈斯 台灣大學資訊工程大二

## 介紹
在2019年初駭客偷了歷史上最大的個人資料庫，包括十億個帳號的密碼。而現在有許多網站由於駭客所到來的影響，就無法向使用者確保100%安全性。也許百分之百安全是一個無法達到的目標。這並非為最近才開始的事情，但因為深度學習的發展，這些駭客很容易就能進接到一個更加厲害的平台去抓他人敏感資料。
實際上我們也可以當白帽駭客，透過深度學習加強我們帳號的安全性。

## Background
There are two general ways of going about hacking a password: dictionary attack and brute force attack. A dictionary attack uses combinations of words in order to generate potential passwords. But using a stochastic permutation might not be ideal. There should be data that password generation is calculated from.
My plan is to use deep learning to optimise the process of creating these words in the form of a dictionary attack.

## Finding Data
There are many, many different types of passwords that require entirely different levels of security. The level of security required for a wifi password versus for an FTP server with sensitive data are massively variant. HexPass is focused on cracking passwords from typical web servers.


## Databases and Files Used
This repository contains every English word in existence, with over 500000 words. https://github.com/dwyl/english-words
