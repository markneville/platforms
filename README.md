<p align="center">
  <a href="https://vercel.com">
    <img src="https://assets.vercel.com/image/upload/v1588805858/repositories/vercel/logo.png" height="96">
    <h3 align="center">Platforms on Vercel</h3>
  </a>
</p>

Welcome to Vercel's Early Access Program for Platforms on Vercel. We're excited you're here! In this repository, you'll find everything you need to get started building a platform on Vercel.

## Introduction

Platforms on Vercel are Vercel customers that allow their users to create unique content pages with a multi-tenant infrastructure. Each user gets assigned a unique subdomain when they create their account, with the (usually paid) option to add a custom domain.

For instance, each writer on Substack has their own unique `.substack.com` subdomain for their newsletters:

- [pomp.substack.com](http://pomp.substack.com/)
- [platformer.substack.com](http://platformer.substack.com/)
- [astralcodexten.substack.com](http://astralcodexten.substack.com/)

Users can also map their custom domains to their `.substack.com` subdomain for an extra fee:

- [platformer.news](http://platformer.news) → [platformer.substack.com](http://platformer.substack.com/)

At Vercel, we want to provide these platforms with a comprehensive solutions for them to build platforms like Substack super easily.

## Examples of Multi-tenant Apps

Multi-tenancy app infrastructures work really well with the following types of apps:

- **Content creation platforms (simple, standardized page layouts/route structure)**
    1. Substack
    2. Medium ([forge.medium.com](http://forge.medium.com/), [marker.medium.com](https://marker.medium.com/))
- **Website/E-commerce Store Builders (complex routing, freeform pages)**
    1. Webflow
    2. [Super.so](http://super.so) (tr.af → traf.super.site)
- **B2B2C platforms (multi-tenant authentication & login)**
    1. Instatus ([sketch.instatus.com](http://sketch.instatus.com/), [linear.instatus.com](http://linear.instatus.com/))
    2. Canny ([framer.canny.io](https://framer.canny.io/), [ahrefs.canny.io](http://ahrefs.canny.io/))

## Supplementary Features

- Analytics
- A/B testing
- OG-image generator
- Auth

## Provide Feedback

- [Start a Discussion](https://github.com/vercel-customer-feedback/platforms/discussions) with a question, piece of feedback, or idea you want to share with the team.
- [Open an Issue](https://github.com/vercel-customer-feedback/platforms/issues) if you believe you've encountered a bug that you want to flag for the team.