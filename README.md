
# E-mail notifications

This repository contains the template sources for AKER kits notifications for Shopify store.

Exported templates are based on four principal mock-ups: cart, digest, kit and source.

Those under `src/export` are intended for importing them on the store.

## How to dev

- Install [yarn](https://github.com/yarnpkg/yarn) and clone this repository
- Move within and run `yarn` to get the dependencies
- Run again `yarn dev` to build everything and start watching

It's good idea to copy a base template, under `src/export` to start hacking!

## How to build

1. Once you got a working template just copy the source-code directly from your browser.
2. Paste it into shopify's custom notifications editor and preview it.
3. if everything works as expected you've done.

Run `yarn dist` if you want a fresh build.

### Orders

- [x] Order confirmation
- [ ] Order canceled
- [ ] Order refund
- [ ] Draft order invoice
- [x] Abandoned checkout
- [ ] POS and mobile receipt

### Shipping

- [ ] Fullfillment request
- [ ] Shipping confirmation
- [ ] Shipping update
- [ ] Shipping out for delivery
- [ ] Shipment delivered

### Customer

- [ ] Customer account invite
- [ ] Customer account welcome
- [ ] Customer account password reset
- [ ] Contact customer
