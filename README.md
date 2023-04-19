This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
### Install


First, run the development server:

```bash
npm install antd
```

Copy `src/components/core` to your component folder

Add this config to `tsconfig.json`. I put `core` folder in `src/components` (replace it by your path)

```
"baseUrl": ".",
"paths": {
  "@components/*": ["src/components/*"]
},
```

In your code, 

```
import { Button } from '@components/core'

export const Demo = () => {
  return (
    <>
      <div>Hi there!</div>
      <p>I'm MrFatMeow</p>
      <Button />
    </>
  )
}
```
