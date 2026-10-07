# Alexander Anufriev

Senior Frontend Developer · Vue · TypeScript · Nuxt

I'm a detail-oriented frontend engineer with 5 years of experience building e-commerce products and reusable tools. I focus on usability, performance, and maintainable code.

I'm looking for a remote frontend role in an international team.

## Product work at [inSales](https://www.insales.ru/)

### Vue product image editor

I owned the frontend architecture and implementation of an editor used by **3,000+ active clients**. Merchants can save editable projects, reuse templates, transfer a composition across product images, and use AI tools without leaving inSales.

### Image editor library

I built the standalone TypeScript/FabricJS library behind the editor, keeping object behavior consistent across copy/paste, templates, and undo/redo. I moved heavy import and export work to Web Workers and made image loading **more than twice as fast**.

### Abandoned Carts

I was the sole frontend developer for a cart-recovery product with **200+ active paid subscribers**. I delivered analytics, cart history, messaging, and trial and subscription states from requirements through release.

### Visual site editor redesign

I implemented the frontend redesign and built a recovery mode that keeps widget settings accessible when the storefront preview fails. After the redesign, the share of new users who independently changed a template or widget setting and saved it in their first session rose from **60% to 80%**.

### Custom Monaco code editor

I led development of a shared code editor used across **five product workflows** and remained its primary maintainer. I built mixed HTML/Liquid language support, cursor-aware autocomplete, and a reusable package for Rails and Vue screens.

### CommonJS storefront library

I modernized and maintained the JavaScript library behind product selection, carts, and customer forms. I reduced its compressed production bundle from **over 300 KB to 168 KB**, while keeping existing templates and custom integrations working.

### Product loading and caching

Within CommonJS, I built AJAX loaders and timestamp-based IndexedDB caching, reducing product-data requests by **approximately 70%**. In representative measurements, product-heavy pages loaded in **2–3 seconds instead of over 5 seconds**.

### Product options and add-ons

I built reusable selection controls and extended the CommonJS cart API for product extras and services. Different add-on combinations stay separate in the cart. Quantity updates target the selected combination, while availability checks account for their combined quantity.

[Projects on LinkedIn](https://www.linkedin.com/in/alexander-s-anufriev/details/projects/) · [Recommendations](https://www.linkedin.com/in/alexander-s-anufriev/details/recommendations/)

## Public projects

### [Fabric Image Editor](https://github.com/Anu3ev/image-editor)

Source code for the image editor library described above, published as `@anu3ev/fabric-image-editor`, with Jest unit tests and Playwright browser tests.

[Try the demo](https://anu3ev.github.io/image-editor/) · [Read the implementation and setup](https://github.com/Anu3ev/image-editor#readme)

### [Relevator Events](https://github.com/Anu3ev/relevator-events)

A Nuxt 4 event application built with TypeScript, Tailwind CSS, DatoCMS, and GraphQL. It includes a paginated event feed, dynamic detail pages, typed data access, and error handling. Originally developed as a take-home assignment.

[Read the architecture and setup](https://github.com/Anu3ev/relevator-events#readme)

## What I work with

- Vue 2/3, TypeScript, JavaScript, and Nuxt
- Canvas interactions, editor state, and undoable workflows
- E-commerce interfaces, admin tools, and API integrations
- Vite, Webpack, Git, and GitHub Actions

## Contact

- [Email](mailto:alexander.s.anufriev@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/alexander-s-anufriev/)
- [Telegram](https://t.me/anu3ev)
