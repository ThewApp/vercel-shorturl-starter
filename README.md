# vercel-shorturl starter

Template for [vercel-shorturl](https://github.com/ThewApp/vercel-shorturl) that automatically deploys using GitHub Actions.

## Demo

[Demo](https://vercel-shorturl-starter.vercel.app) is deployed with the example [redirects.yml](redirects.yml).

## Usage

1. [Create a new repository from this template](https://github.com/ThewApp/vercel-shorturl-starter/generate)
1. [Add the following secrets](https://docs.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-secrets#creating-encrypted-secrets-for-a-repository) to your repository:
   - `VERCEL_TOKEN`: You vercel account token obtained from https://vercel.com/account/tokens
   - `VERCEL_PROJECT`: Content of the `.vercel/project.json` file generated by running `vc link` command in any empty directory.
1. Edit `redirects.yml`

Then GitHub Actions will deploy to Vercel every time you make a change and every 5 days to prevent `VERCEL_TOKEN` expiration

## Features

For more features please visits [vercel-shorturl](https://github.com/ThewApp/vercel-shorturl#features).