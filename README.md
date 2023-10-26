# UberEatsBot

UberEatsBot is a Python script designed to find and apply unused promo codes automatically during the UberEats checkout process. With this bot, you can potentially save up to 100% on your UberEats order.

## How it works
Some people receive promo codes for up to 100% off on their order after an order has been misplaced or items went missing, directly from uber. Some of these codes tend to go unused, and I have found the exact format they follow, and how to crack them so I can use them myself.
This bot uses selenium to spam as many of these promocodes as possible, and stops when a 100% off code has been found.

Despite the name being "**UberEats**Bot", this bot actually works for deliveroo and grubhub too, albeit it does take slightly longer.

Avg times for each delivery service to get a 80% off code or above:
- **UberEats** : ~6 minutes
- **Deliveroo** : ~9 minutes
- **GrubHub** : ~11 minutes
This likely works for other delivery services too, but I simply haven't tested them extensively, so try them on your own.

## Features
- Automated brute forcing of promo codes.
- Simple TKinter GUI.
- No input necessary, sit back and relax.

## How to use
1. Run the bot while on the checkout page of your ubereats, just before payment.
2. The bot should automatically detect what browser you are using and find your web page (be patient, this might take a few minutes depending on the speed of your PC.)
3. The GUI should appear, set what % discount to stop at, and press "Start searching" to begin.
4. You can minimize the window and simply wait, a "beep" sound will be played when the bot is done.
5. Enjoy your discount!

## Disclaimer

This script is for educational purposes only, and is not officially licensed to be used by UberEats or other delivery services. This bot may be patched eventually, please check back often for updates.

It is not recommended to use this bot for every order, as it is unlikely delivery services would be happy when they see you getting 100% off 3 orders in a row.
