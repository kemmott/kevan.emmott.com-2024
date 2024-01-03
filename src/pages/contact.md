---
title: Contact
seo:
  title: Contact
permalink: /contact/index.html
description: Contact info
layout: page
---

{{ meta.address.firma }}
{{ meta.address.street }}
{{ meta.address.zip }}, {{ meta.address.city }}

Tel: <a href="tel:{{ meta.address.mobileCall }}">{{ meta.address.mobileDisplay }}</a>
Mail: <a href="mailto:{{ meta.address.email }}">{{ meta.address.email }}</a>
