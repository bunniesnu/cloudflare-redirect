# Cloudflare Redirect

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?logo=cloudflare&logoColor=white)

A Cloudflare workers project for simply returning a 301 permanent redirect response.

## Requirements

* A Cloudflare account

## Usage

Simply configure a new Cloudflare Workers, and link to github public repository: ```https://github.com/bunniesnu/cloudflare-redirect```

After building, set the desired redirect URL to a runtime variable named: ```REDIRECT_URL```

If you access to your workers URL, you will be redirect to the URL!