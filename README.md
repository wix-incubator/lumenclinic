# Lumen Clinic

Lumen Clinic is a calm healthcare appointment experience for service selection, appointment availability, patient details, booking creation, and confirmations.

This website is powered by Wix Headless and built using [wix-headless.dev](https://www.wix-headless.dev).

## Links

- Live site: [https://lumen-clin-861ded42-gonenj.wix-site-host.com](https://lumen-clin-861ded42-gonenj.wix-site-host.com)
- Source: [https://github.com/wix-incubator/lumenclinic](https://github.com/wix-incubator/lumenclinic)
- Wix site ID: `3b04ea7a-cf6a-4de7-9d0a-312052a0f2ce`

## What It Showcases

- A custom Astro appointment journey backed by Wix Bookings.
- Service discovery, availability lookup, and appointment slot selection.
- Patient information capture and booking creation.
- Paid or premium appointment handoff through Wix eCommerce checkout.
- Redirect handling for checkout and confirmation flows.
- Public `robots.txt` and `llms.txt` configured through Wix SEO txt APIs.
- Deployment with `wix release`.

## Wix Solutions Used

- Wix Headless Site for the managed site/runtime foundation.
- Wix Bookings for services, availability, and appointment booking.
- Wix eCommerce for paid appointment checkout.
- Wix Redirects for checkout/confirmation redirects.

## Wix SDKs And Packages

- `@wix/astro`
- `@wix/astro-pages`
- `@wix/sdk`
- `@wix/bookings`
- `@wix/ecom`
- `@wix/redirects`

## Local Development

Create a local env file from `.env.example` or run the Wix CLI env setup for the connected site.

```bash
npm install
npm run dev
```

## Build And Release

```bash
npm run build
npm run release
```
