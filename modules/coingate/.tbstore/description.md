# Thirtybees CoinGate Plugin

Accept Bitcoin & Altcoins on your Thirtybees store.

Read the module installation instructions below to get started with CoinGate Bitcoin & Altcoin payment gateway on your shop.
Full setup guide with screenshots is also available on our blog: <https://blog.coingate.com/2017/04/install-prestashop-bitcoin/>

**Plugin is compatible with Thirtybees 1.0.0 or greater version**

## Install

Sign up for CoinGate account at <https://coingate.com> for production and <https://sandbox.coingate.com> for testing (sandbox) environment.

Please note, that for "Test" mode you **must** generate separate API credentials on <https://sandbox.coingate.com>. API credentials generated on <https://coingate.com> will **not** work for "Test" mode.

Also note, that *Receive Currency* parameter in your module configuration window defines the currency of your settlements from CoinGate. Set it to BTC, EUR or USD, depending on how you wish to receive payouts. To receive settlements in **Euros** or **U.S. Dollars** to your bank, you have to verify as a merchant on CoinGate (login to your CoinGate account and click *Verification*). If you set your receive currency to **Bitcoin**, verification is not needed.

### via Thirtybees FTP

1. Download <https://github.com/coingate/thirtybees-plugin/archive/1.0.0.zip>

2. Upload extracted content to your Thirtybees root folder.

3. Go to your Thirtybees admin panel » **Modules and Services**.

4. Find **Cryptocurrency Payments via CoinGate** and click **Install** button to next to it, then click **Proceed with the installation**.

5. Enter your [API credentials](https://support.coingate.com/en/42/how-can-i-create-coingate-api-credentials) (*Auth Token*). Configure **Receive Currency** and click **Save**.
