# Hack

Stripe.js Does not initialize When Using a live api key within a React Native WebView with a local file as the source because Stripe.js checks for TLS encyption somehow. The solution is to host the source on a https enabled server. This was completely a shot in the dark, the error just says {name: IntergrationError}. I cried when the form loaded properly.
