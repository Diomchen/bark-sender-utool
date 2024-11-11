# Utools - Bark Sender 

English | [中文](./doc/README-zh.md)
## About
A utools plugin.

You can use Bark for custom encrypted push notifications, allowing the transmission of sensitive text information such as account passwords and wallet private keys.

## Dependency
* [Finb/Bark](https://github.com/Finb/Bark)
* [Finb/bark-server](https://github.com/Finb/bark-server)

## Install 
### Step 1
[Download](https://github.com/Diomchen/bark-sender-utool/releases/tag/v0.0.1) the latset plugin file.

### Step 2
[ How to install uTools plugin app offline ](https://www.u.tools/docs/guide/faq.html#%E5%A6%82%E4%BD%95%E7%A6%BB%E7%BA%BF%E5%AE%89%E8%A3%85-utools-%E6%8F%92%E4%BB%B6%E5%BA%94%E7%94%A8)

## How to use
### Step 1 
Open your mobile's **Bark** app, and find the `推送加密`.

![](https://fastly.jsdelivr.net/gh/Diomchen/PiCor/20241111111357.png)

<br>

Only support `AES-128`、`CBC`、`pkcs`. Then you need to  customize `Key` and `Iv` parameters.

![](https://fastly.jsdelivr.net/gh/Diomchen/PiCor/20241111111509.png)

### Step 2 
Open uTools, and input key-words `bk`、`bark`.
![](https://fastly.jsdelivr.net/gh/Diomchen/PiCor/20241111111816.png)


### Step 3
Set encryption config.
![](https://fastly.jsdelivr.net/gh/Diomchen/PiCor/20241111112434.png)


