# Optimistic UI

## One-Click Deploy

Deploy your own SWR project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/project?template=https://github.com/vercel/swr/tree/master/examples/optimistic-ui)

## How to Use

Download the example:

```bash
curl https://codeload.github.com/vercel/swr/tar.gz/master | tar -xz --strip=2 swr-master/examples/optimistic-ui
cd optimistic-ui
```

Install it and run:

```bash
yarn
yarn dev
# or
npm install
npm run dev
```

Deploy it to the cloud with [now](https://vercel.com/home) ([download](https://vercel.com/download))

```
now
```

## The Idea behind the Example

Example of how to use SWR to implement an Optimistic UI pattern where we mutate the cached data immediately and then trigger a revalidation with the API.
