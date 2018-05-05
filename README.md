# Hack

Stripe.js does not initialize When using a live api key within a React Native WebView with a local file set as the source because Stripe.js somehow checks for TLS encyption on the originating page request. The solution is to host the source with https. This was completely a shot in the dark, the error just says {name: IntergrationError}. I cried when the form loaded properly.
