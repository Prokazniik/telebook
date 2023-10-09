# Telegram Mini App Payments

This guide contains information about how to implement payments in your Telegram Mini App

### How to create receive "payment_token"

1. Open BotFather and call `/mybots`
2. From the menu select your bot
3. From the Inline Keyboard press Settings -> Payments
4. Select "Stripe test" system
5. Open Stripe bot and follow instructions
6. When you will be asking to create a Stripe test account, follow the [Testing Stripe Connect](https://stripe.com/docs/connect/testing#account-numbers) guide
7. After you create the Stirpe account, you will receive the "payment_token" from BotFather

### How to make test payments