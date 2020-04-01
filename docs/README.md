# Why PostHog?

## Understand each user's behavior

Before you build that next feature, understand how people are using what you already built.

## Know who is quitting your app

Create funnels - work out where users commonly drop out.

## Track which features are popular

Visualize trends in your product usage.

## The only developer friendly option

Full underlying data access.
Docker/Heroku or source deployment.
Host the entire thing with the rest of your product.

# Quick Start

## Heroku (easiest)

[1-click Deploy](https://heroku.com/deploy?template=https://github.com/posthog/posthog)

## Docker

Copy-paste this into your terminal:

```
docker run -t -i --rm --publish 8000:8000 -v postgres:/var/lib/postgresql posthog/posthog:preview
```