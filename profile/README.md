<div align="center">
  <img alt="micro-lc logo" src="https://raw.githubusercontent.com/micro-lc/.github/main/profile/img/micro-lc_logo.png" width="300" />
</div>

# Welcome to micro-lc

micro-lc is a lightweight **micro-frontend orchestrator** that helps building flexible and multi-tenant frontend applications bringing together multiple [micro-frontend](https://micro-frontends.org/) patterns.
The project started in 2021 within [Mia-Platform](https://github.com/mia-platform), and was launched open source in 2022 after several months of production usage.

## Why micro-lc?

🎼 micro-lc is an open source **micro-frontend orchestrator**.

🧱 micro-lc offers a solution for building **flexible**, **multi-tenant** frontend applications.

🖼 micro-lc is well suited to build **any type of web application**, from classical top-bar/sidebar multi-pages websites, to CMSs, blogs, or even applications with no layout at all.

⚡ micro-lc aims to be as **lightweight** as possible and to improve **web security**.

🔗 micro-lc brings together **different micro-frontend patterns** inside the same application.

🏃 micro-lc consists of a core interface that loads, embeds, and orchestrates individual frontend applications at **runtime**, while providing **configuration options** and useful **out-of-the-box features**.

## Features

micro-lc supports three different micro-frontend patterns at the same time:
1. [iframes](https://micro-lc.io/docs/guides/applications/iframes),
2. [parcels](https://micro-lc.io/docs/guides/applications/parcels),
3. [shadowed components](https://micro-lc.io/docs/guides/applications/compose).

An **iframe** is an external websites embedded into our application.
A **parcel** instead is a fully-fledged (possibly single-page) application which lives within the context of the main application, but is JS-sandboxed and routed.
Finally, **shadowed components** refer to business logic encapsulation via web components which allows to protect from style leaks
and to scope events using HTML5 elements Shadow DOM.

Orchestration happens at **run-time** so that a JSON (or YAML) configuration is all <micro-lc></micro-lc> needs to add
a new micro-frontend application. Configurations can be **hot-swapped** or edited at run time, meaning a page refresh is
enough to preview your application after config changes.

micro-lc provides a **smooth navigation experience** between different applications, SPAs, and iframes while wrapping them in a static layout.

It ships as a [CDN bundle](https://micro-lc.io/docs/getting-started#import-from-cdn) that can be embedded into HTML pages or other scripts,
and as a [Docker container](https://micro-lc.io/docs/getting-started#deploy-docker-container) that can be configured with volumes.

micro-lc is heavily inspired by and based on micro-frontend orchestration tools such as
[single-spa](https://single-spa.js.org/) and [qiankun](https://qiankun.umijs.org/).

By orchestrating micro-frontend applications, micro-lc achieves a fair amount of benefits:
* applications written in **different frameworks** can live together on the same page;
* applications can be deployed **independently**;
* applications can **communicate** through standard APIs leveraging also event-driven patterns.

Compared to other tools, micro-lc provides:
* live configuration and preview;
* centralized styling APIs;
* HTML-like composition tools (_lit-html_);
* import map integration (_es-module-shims_).

## Resources

* Official Documentation: [micro-lc.io](https://micro-lc.io/)
* Read the official announcement: [micro-lc: the new open-source project for micro frontend orchestration](https://blog.mia-platform.eu/en/micro-lc-the-new-open-source-micro-fronted-orchestrator)
* New to micro-frontends? [Micro frontends: how to manage chaos in a monolithic world](https://blog.mia-platform.eu/en/micro-frontends-how-to-manage-chaos-in-a-monolithic-world)
* Get started with the [Playground](https://micro-lc.io/playground/)

# Other open source projects supported by Mia-Platform

* [Rönd](https://github.com/rond-authz): a lightweight container that distributes security policy enforcement
* [kube-green](https://github.com/kube-green): a k8s operator to reduce CO2 footprint of your clusters
