
---

## `vc-site/README.md`

```md
# vc-site

Static portfolio website for `vikalchoudhary.com`.

## Overview

This repository contains the source code for my personal portfolio website.

The site is built with Hugo and deployed to an AWS EC2 instance. Deployment is automated through GitHub Actions.

## Stack

- Hugo
- GitHub Actions
- AWS EC2
- Nginx
- Cloudflare DNS / HTTPS

## What this repo does

This repository is responsible for:

- website content
- page layouts
- Hugo configuration
- static site generation
- automated deployment on push

It does not manage infrastructure. Infrastructure and server configuration live in the `vc-infra` repository.

## Repository structure

```text
vc-site/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── archetypes/
├── content/
├── layouts/
├── static/
├── hugo.toml
└── README.md
