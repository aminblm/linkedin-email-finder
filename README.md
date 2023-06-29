# The LinkedIn Email Finder

### A node web scraper to extract your linkedin connection emails

![demo-part-1](https://github.com/aminblm/linkedin-email-finder/assets/25132838/4245d582-3599-4b98-a3c6-b06454c29921)


## Important Note
Scraping data off of LinkedIn is against their [User Agreement](https://www.linkedin.com/legal/user-agreement). This is purely intended for educational purposes.

## Why?
LinkedIn allows you to export all of your connections' info into a csv, except for their emails. 
Additionally their API stopped allowing the extraction of emails around 2013-2014. Why don't we have access to our connections emails through their data export if we both agreed to share that info/data?


To modify, use, get documentation or for you enquiries kindly contact me via: <br>
**amin@boulouma.com**

## Donation and Support 🥳

With your support I build, update and work on this project. You can also purchase additional packages, tutorials and materials explaining how this bot is working. <br>

There are several features and simplifications I'd like to add to this project. For that I need your support to cover costs. Your support is keeping this project alive.

[**Donate & support!**](https://commerce.coinbase.com/checkout/576ee011-ba40-47d5-9672-ef7ad29b1e6c)

## Purchase additional materials and guides 😍

You can currently, purchase full in depth detailed tutorial explaining how this bot is working, one hour booking session where i step by step build and run the bot on your machine or 5 videos
showing how this can be used. To buy, support this project and help me add more features. <br>

- [**Purchase working videos for this bot**](https://commerce.coinbase.com/checkout/3958599d-3938-4fb3-86f4-b100c2d7e850)
- [**Purchase online call tech support to install the bot for Windows**](https://commerce.coinbase.com/checkout/638f5582-a750-4374-86ea-82d0445cbe90)
- [**Purchase online call tech support to install the bot for Linux**](https://commerce.coinbase.com/checkout/3ec705fe-2898-4ae8-9f90-73cd1270392f)
- [**Purchase online call tech support to install the bot for Mac OS**](https://commerce.coinbase.com/checkout/cf76021c-53be-42bc-8ae1-2dc75fcd9647)
- [**Purchase documentation of this bot for Windows**](https://commerce.coinbase.com/checkout/ac4212d1-ecb0-4734-8946-f4a9e5c09f45)
- [**Purchase documentation of this bot for Linux**](https://commerce.coinbase.com/checkout/69a1f1b8-3282-4ab6-9383-6ce28aab3274)
- [**Purchase documentation of this bot for Mac OS**](https://commerce.coinbase.com/checkout/c7069064-02ac-4c3b-b980-ae7623bc8139)


## Installation
- Clone this repo `git clone https://github.com/FutoRicky/linkedin-email-extractor.git` or download
- Move into the repo directory `cd linkedin-email-extractor`
- Install dependencies `npm install`

## How to Use
- You will need the `Connections.csv` file that LinkedIn provides with the data export. 
  - [Instructions on how to export connections from LinkedIn](https://www.linkedin.com/help/linkedin/answer/66844/exporting-connections-from-linkedin?lang=en)
- Add the `Connections.csv` file into the `linkedin-email-extractor` directory
- Run `npm start` or `node --harmony index.js`
- Enter LinkedIn Credentials when prompted
- Wait for email extraction process to finish
- An `email.txt` file will be generated with all the emails inside the `stored_data` folder.

## LinkedIn UI Versions
If your panel looks like this, then you are still on the `old` version, use a version <= 1.1.1:

[![Screen-Shot-2019-01-30-at-4-12-12-PM.png](https://i.postimg.cc/L8N31bfb/Screen-Shot-2019-01-30-at-4-12-12-PM.png)](https://postimg.cc/3k0GM9tX)

If your panel looks like this, then you are one the `new` version:

[![Screen-Shot-2019-01-30-at-4-14-34-PM.png](https://i.postimg.cc/rpsCCNNF/Screen-Shot-2019-01-30-at-4-14-34-PM.png)](https://postimg.cc/XZMCnFPT)

## Issues extracting? Read This

If linkedin updates their page and changes the class of an element used in the script it will stop working. You can check out the source code and verify if any class has changed on linkedin and update the script to make it work again. I can't be constantly checking linkedin to see if they have changed something that breaks the script.
