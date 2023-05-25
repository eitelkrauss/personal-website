---
layout: '../layouts/resume.astro'
---
# Eitel Krauss

Web developer with a strong UX and design sense.  Based in Ecuador.
<br>
## Skills

- Hybrid rendered apps with [Nuxt 3][nuxt]

- Web apps (SPA) with Vue 3
- Web Components with [Lit Element][lit-dev]
- Static sites with [Astro][astro]
- Semantic HTML5, CSS/Tailwind
- Typescript
- Express, Node JS, Prisma
<br>
## Experience

### _Frontend Engineer_ @ [Eclipsoft][eclipsoft]
2022 - Present

#### Projects:

- #### [Onboarding][onboarding]

  A hybrid app built with Nuxt 3.  It's a white brand template for companies to implement their onboarding process.  From openning a bank account to applying for credit.  
  An onboarding process usually includes a face recognition and/or liveness validation step, so we integrated [ID4Face][id4face] to handle it, which is a framework agnostic web component I describe below.
  Like any onboarding process it comes with a form.  This form is rendered dynamically from a JSON provided by an API and can be edited on the admin site like a CMS.  
  The process ends with a contract (a PDF document) signed electronically with a one-use electronic signature certificate and sent to both the company and the user's specified email.
  

- #### [ID4Face][id4face]

  Used Lit Element to build a web component (in this case a modal) that does passive liveness validation and face recognition with a Mediapipe model.  The purpose for this is being able to implement it on any website or app with minimal effort. 
  You can provide a base64 image for reference or you can use an integrated service that pulls the end user's data from the national registry office in Ecuador and uses the image stored in their database for the comparison.
  You can try it by uploading a picture to use as reference image.  It communicates with a Java backend API that does some extra liveness validation with Amazon Rekognition.

- #### Branded CSS design system

  Worked closely with the design team to implement stylesheets to be shared across all company products to keep a consistent branding style
<br>

### _Web Developer and Designer_ @ Freelance
2017 - 2022
#### Projects:

- #### [BCHWOOD.COM][bchwood]
  
  An E-commerce site built with Vue JS.  It uses a headless CMS for the backend with Strapi.io  It implements Paymentez which is a LatAm based payments processor.
<br>
## Education

### _Design and Visual Communications_ @ Universidad Casa Grande
Guayaquil, Ecuador 2013 - 2017

<br>

## Contact
You can reach me at <eitelkrauss@protonmail.com>  

Looking forward to chatting with you!

Github [@ekrausso][github]


[astro]: <https://astro.build>
[github]: <https://github.com/ekrausso>
[nuxt]: <https://nuxt.com>
[lit-dev]: <https://lit.dev>
[eclipsoft]: <https://eclipsoft.com>
[bchwood]: <https://bchwood.com>
[id4face]: <https://id4face.eclipsoft.com>
[onboarding]: <https://onboarding.eclipsoft.dev>