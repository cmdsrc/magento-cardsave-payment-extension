magento-cardsave-payment-extension
==================================

Official Magento payment extension for the CardSave Online payment gateway. This extension fully supports the processing of 3D secure (Verified By Visa and Mastercard SecureCode) transactions. It also supports all of the integration methods provided by CardSave:

- Direct (API) Integration - customer never leaves your site during the payment process. Requires an SSL certificate. Card details DO get posted back to your site, which slightly affects your PCI DSS requirements.
- Hosted Payment Form - customer jumps across to a payment form hosted on CardSave's systems. Doesn't require an SSL certificate
- Transparent Redirect - customer never *appears* to leave your site during the payment process. Requires an SSL certificate. Card details get posted directly across to CardSave's system, so this method has the same PCI DSS requirements as the Hosted Payment Form.

[http://www.magentocommerce.com/magento-connect/cardsave-payment-extension-official.html](http://www.magentocommerce.com/magento-connect/cardsave-payment-extension-official.html)
