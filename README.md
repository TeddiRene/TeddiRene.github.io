# TeddiRene.github.io
Teddi Rene pages
<!DOCTYPE html>
<html>

<head>
  <title>Brown Bears</title>
</head>

<body>
  // Require the Stripe library with a test secret key.
const stripe = require('stripe')('sk_test_BQokikJOvBiI2HlWgH4olfQ2');

// Create a payment from a test card token.
const charge = await stripe.charges.create({
  amount: 2000,
  currency: 'usd',
  source: 'tok_mastercard',
  description: 'My first payment'
});

// Click “▶ run” to try this code live and create your first payment.
</body>

</html>
