
# SSL Server Certificate

A shell script to create Server SSL Certificate.
![Logo](https://now.symassets.com/content/dam/norton/global/images/non-product/misc/tlc/how-ssl-certificates-work.png)



# What is SSL Certificate

An SSL certificate is essential for all websites, not just those that sell products. If you own a website you need an SSL certificate for your website. It's as simple as that. Having an SSL certificate is no longer a luxury, it's a necessity.

There are a number of benefits to having an SSL certificate. They include:

⚫SSL protects sensitive information.
⚫SSL affirms your business identity and improves customer trust.
⚫Better search engine ranking.
⚫SSL helps you satisfy PCI/DSS requirements.

## Run on server

Clone the project

```bash
  git clone https://github.com/ayush12993/SSL-Certificate-Script
```


Go to the project directory

```bash
  cd SSL-Certificate-Script
```
Before using this script make sure to edit this --
```shell
/C=yourcountry/ST=yourstate/L=yourcity/O=yourorganization/OU=Education/CN=*.yourdomain/emailAddress=youremailaddress
```
Run this script as root -

```bash
sudo chmod +x cert.sh
sudo ./cert.sh
```

List all the files

```bash
  ls
```

