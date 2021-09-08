# shc-covid19-decoder

Fork of https://fproulx.github.io/shc-covid19-decoder/ with the hard coded key
changed to use BC's keys instead of Quebec's.

https://smarthealthcard.phsa.ca/v1/issuer/.well-known/jwks.json

Visit simple hosted version on your phone (does NOT transmit any data, all remains in your browser)

About
Very simple app to decode your Vaccination Proof QR Code - Compatible with SHC (Smart Health Card standard).

![decoder-page](decoder-page.jpeg)
![demo](demo.png)

# Building

- `npm run build` compiles the JS
- `npm run dev` compiles the JS in watch mode
