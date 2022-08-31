This is a [RainbowKit](https://rainbowkit.com) + [wagmi](https://wagmi.sh) + [Next.js](https://nextjs.org/) project bootstrapped with [`create-rainbowkit`](https://github.com/rainbow-me/rainbowkit/tree/main/packages/create-rainbowkit).

# Socket V2 Widget with Rainbowkit

This is a PoC to demonstrate using the (Socket Widget)[https://github.com/SocketDotTech/widget] with RainbowKit

The main isses are that the module can only be loaded with SSR because the widget uses browser APIs in the module entry

The other issue is getitng the right provider from `wagmi`.

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.
