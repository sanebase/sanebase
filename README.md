<picture>
  <source srcset="https://raw.githubusercontent.com/sanebase/docs/refs/heads/main/logo/dark.svg" media="(prefers-color-scheme: dark)">
  <source srcset="https://raw.githubusercontent.com/sanebase/docs/refs/heads/main/logo/light.svg" media="(prefers-color-scheme: light)">
  <img src="https://raw.githubusercontent.com/sanebase/docs/refs/heads/main/logo/light.svg" alt="Sanebase logo">
</picture>

<!-- ![GitHub Repo stars](https://img.shields.io/github/stars/sanebase/sanebase) -->
[![Read the Docs](https://img.shields.io/badge/Read%20the%20Docs-3473AF)](https://docs.sanebase.dev/)
[![Sanebase Cloud](https://img.shields.io/badge/Sanebase%20Cloud-52802D)](https://sanebase.dev)


**Keep your app in sync with Stripe without going mad**

---

### What is Sanebase?

Sanebase simplifies the process of keeping your app in sync with Stripe using techniques and infrastructure that are used in production by established engineering teams serving millions of customers.

<picture>
  <source srcset="https://raw.githubusercontent.com/sanebase/docs/refs/heads/main/images/sanebase-vs-now-3-dark.png" media="(prefers-color-scheme: dark)">
  <source srcset="https://raw.githubusercontent.com/sanebase/docs/refs/heads/main/images/sanebase-vs-now-3.png" media="(prefers-color-scheme: light)">
  <img src="https://raw.githubusercontent.com/sanebase/docs/refs/heads/main/images/sanebase-vs-now-3.png" alt="Sanebase vs Now">
</picture>

<center style="font-size:0.95rem">

Sanebase in [Unified Ingest](https://docs.sanebase.dev/sync-modes/choose) sync mode

</center>

---

### Do you even need this?

If you’ve ever processed real customer transactions in production, even at a small scale, you already know what a nightmare it is to stay in sync.

![Webhook Iceberg](https://raw.githubusercontent.com/sanebase/docs/refs/heads/main/images/iceberg.png)

You can read more [here](https://docs.sanebase.dev/why-sanebase).

---

### Sanebase Cloud
Get all of the magic with a few lines of code, without the complexity of maintaining it yourself, at a fraction of the cost or free.

[Check it out &rarr;](https://sanebase.dev/)

---

### Open source vs Cloud

The cloud service builds on top of the open source core and comes with additional functionality.

Sanebase started as an internal service, and we decided to restructure it and launch it as a product. We want to give developers an open-source option that they can self-host, so we re-built the entire platform around a highly simplified core + plugin architecture. We then re-implemented a simplified version of our [Unified Ingest mode](https://docs.sanebase.dev/sync-modes/unified-ingest/overview) that is easy to self-host and manage at a reasonable cost.

We also offer a free plan in the Cloud service that contains all the features that the open source version has + a lot more, with some limits depending on the amount of revenue processed. You can see the pricing [here](https://sanebase.dev/pricing).

You can read more about [Open Source vs Cloud here](https://docs.sanebase.dev/open-source-vs-cloud), including the costs involved to self-host.

---

### License & Usage

The open source version is available under the [AGPL v3](https://github.com/sanebase/sanebase/blob/main/LICENSE) license and is free for self-use (personal or internal business use).

Commercial hosting, SaaS offerings, or reselling Sanebase as a service is prohibited without explicit written permission.

The terms for the cloud service are available [here](https://sanebase.dev/terms).
