## *Please note that we do not serve U.S. registered businesses due to regulatory reasons yet.*

Accept cryptocurrency payments in your Thirtybees store with [CoinGate](https://coingate.com/) - our fully automated payment processing and invoice system makes it easy, convenient, and risk-free for you and your customers.

With a simple installation of the CoinGate Thirtybees extension in your store's checkout, customers can pay for your goods and services with cryptocurrencies like Bitcoin, Litecoin, Ethereum, Bitcoin Cash, and XRP, among 50+ other altcoins.

With CoinGate’s Thirtybees plugin, merchants can also receive real-time settlements of cryptocurrencies in *Euros - payouts are made directly to your bank account*. This way, businesses are not exposed to price volatility risk and can enjoy fixed payouts no matter the cryptocurrency’s price.

Alternatively, store owners can choose to receive *payouts in cryptocurrency as well*.

### Features:

- The gateway is fully automatic – set it and forget it.
- Receive automatic payment confirmations and order status updates.
- Set your prices in any local fiat currency, and the payment amount in cryptocurrency will be calculated using real-time exchange rates.
- [Customize the invoice](https://blog.coingate.com/2019/03/how-to-customize-merchants-invoice-guide/) – disable/enable cryptocurrencies, change their position on the invoice, and more.
- Select the [settlement currencies and payout options](https://blog.coingate.com/2019/08/payouts-fiat-settlements/) for each crypto-asset;
- Use a [sandbox environment](https://sandbox.coingate.com) for testing with Testnet Bitcoin.
- No setup or recurring fees.
- No chargebacks – guaranteed!

### Functionality:

- [Extend invoice expiration time](https://blog.coingate.com/2017/09/bitcoin-merchant-extend-invoice-expiration-time/) up to 24 hours (if payouts are in BTC).
- Accept slight underpayments automatically.
- Refunds can be issued directly from the invoice and without the involvement of the seller.

### How it works - an example:

1. An item in the store costs 100 euro.
1. A customer wants to buy the item and selects to pay with Bitcoin.
1. An invoice is generated and, according to the current exchange rate, the price is 10000 euro per bitcoin, so the customer has to pay 0.01 bitcoins.
1. Once the invoice is paid, the merchant receives 99 euro (100 euro minus our 1% flat fee), or 0.0099 BTC.

*If you’re having trouble installing the plugin, check our blog for a more in-depth description at https://blog.coingate.com/2020/08/thirty-bees-accept-btc-payments/*

To use a plugin, a business is required to [pass the verification](https://blog.coingate.com/2019/05/verify-merchant-account-faq/) or [apply for a trial account](https://blog.coingate.com/2019/05/verify-merchant-account-faq/) first.

Any questions? Write to our support team at support@coingate.com

### Plugin is compatible with Thirtybees 1.0.0 or greater version

## Installation

Sign up for a CoinGate account at https://coingate.com for production and https://sandbox.coingate.com for testing (sandbox) environment.

Please note that for "Test" mode you must generate separate API credentials on https://sandbox.coingate.com. API credentials generated on https://coingate.com will not work for "Test" mode.

Also note, that the Receive Currency parameter in your module configuration window defines the currency of your settlements from CoinGate. Set it to BTC, EUR or USD, depending on how you wish to receive payouts.

### via FTP
1. Download https://github.com/coingate/thirtybees-plugin/releases/download/v1.0.0/CoinGate_Thirtybees-1.0.0.zip
1. Upload extracted content to your Thirtybees root folder.
1. Go to your Thirtybees admin panel » Modules and Services.
1. Find Cryptocurrency Payments via CoinGate and click the Install button next to it, then click Proceed with the installation.
1. Enter your [API credentials](https://support.coingate.com/en/42/how-can-i-create-coingate-api-credentials) (*Auth Token*). Configure Receive Currency and click Save.
