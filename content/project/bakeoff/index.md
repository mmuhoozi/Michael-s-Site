---
title: "KRASS Training Sessions"
subtitle: "A Consulting firm for research in health, education and social services."
excerpt: "This theme has a form-to-email feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the form front matter."
date: 2019-07-01
author: "Michael Muhoozi"
draft: false
tags:
  - hugo-site
categories:
  - Theme Features
  - R
  - package
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: https://bakeoff.netlify.com/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/apreshill/bakeoff
---



![Formspree Logo](formspree-logo.png)

## [Formspree](https://formspree.io) makes it easy to for your organization to increase productivity by ensuring trainees to understand how to solve day to day challenges at work while learning the best there is in research!!!

---

### Qualitative Research Training

This aims to equip participants with the knowledge and skills to design, conduct, and interpret qualitative research. A team also provides sessions on using qualitative software like Atlas ti and Nvivo. This is done by friendly and approachable team that is  available to offer tailored feedback during the course. 
This theme has a **form-to-email** feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the front matter of the form
(`/content/forms/contact.md`). Of course, the example shown below (`your@email.here`) must not be used. Please use your actual email address.

```toml
# please replace with a valid Formspree form id or email address
formspree_form_id: your@email.here
```

Update that file and you're ready to begin receiving submissions. Just submit
the active form for the first time, and complete the email address verification
step with Formspree, and your contact form is live. The next time someone
fills it out, the submission will land in your inbox.

### Quantitative Research Training

Quantitative Methods in offers practical sessions epidemiology and biostatistics. This is premised on Ugandan use cases and open data to derive key practical knowledge from experienced professionals. The training also offers sessions on using R and stata for data analysis. 
The files included with the theme have a contact page ready for copy/paste, or
you can type `hugo new forms/contact.md` and you're off to the races. There are two
layouts for `forms` – `split-right`, and `split-left` – you guessed it, one puts
the form on the right and the other on the left. You just fill out the front
matter, and the rest is automatic.

```toml
# layout options: split-right or split-left
layout: split-right
```

![Contact Form Split Right Layout Screenshot](built-in-contact-form-screenshot.png)

Both layouts display the page title and description opposite the form, and you
can also choose to show your social icon links if you have those configured in
the `config.toml` file.
