# Wardrobe template

A complete starting point for a clothing store: catalogue with colours and sizes, stock, orders, payments, shipping and returns, with an editorial website, a back office and a customer app.

| Folder | What it is | Stack | Runs on |
| --- | --- | --- | --- |
| [`backend`](backend) | API shared by the website, admin and app | Django, Django REST Framework | `localhost:8001` |
| [`website`](website) | Public shop: home, catalogue, product pages, bag, checkout, account | Astro | `localhost:4322` |
| [`admin`](admin) | Back office: sales, orders, products, stock, returns | Angular | `localhost:4201` |
| [`customer-app`](customer-app) | Mobile app for customers | Flutter | iOS and Android |

Each folder is a Git submodule with its own repository. The demo brand, "Halden", and everything about it are fictional; product photos come from Unsplash and are credited wherever they appear.

## Getting started

```bash
git clone --recurse-submodules https://github.com/mattoznav/templates-wardrobe.git
```

Start the backend first (see its README), then the website, the admin and the app. The ports differ from the cinema template so both can run at the same time.

Part of the [`templates`](https://github.com/mattoznav/templates) collection.
