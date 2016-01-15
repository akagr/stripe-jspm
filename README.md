# stripe-jspm

This is a simple wrapper over [stripe.js](https://stripe.com/docs/stripe.js) to allow installing and importing in apps using jspm.

It can be installed as:

```bash
jspm install stripe=github:akagr/stripe-jspm
```

And can then be easily be required and used.

```javascript
import 'stripe';

Stripe.setPublishableKey('pk_test_6pRNASCoBOKtIshFeQd4XMUh');
```

