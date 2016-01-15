# stripe-jspm

This is a simple wrapper over [stripe.js](https://stripe.com/docs/stripe.js) to allow installation and importing it in apps using jspm. Currently it exposes a global called Stripe which is not very jspm-ish. However that's coming from stripe.js.

It can be installed as:

```bash
jspm install stripe=github:akagr/stripe-jspm
```

It can then be easily be required and used.

```javascript
import 'stripe';

Stripe.setPublishableKey('pk_test_6pRNASCoBOKtIshFeQd4XMUh');
```

