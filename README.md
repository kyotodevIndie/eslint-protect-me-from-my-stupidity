# Eslint Protect Me From My Stupidity

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

Install dependencies:

```
npm i -D eslint-protect-me-from-my-stupidity
```

  or

```
yarn add -D eslint-protect-me-from-my-stupidity
```

Inside `.eslintrc.json`

##### React (with Next.js)

```
{
  "extends": [
    "eslint-protect-me-from-my-stupidity/next", 
    "next/core-web-vitals"
  ]
}
```

##### React (without Next.js)

```
{
  "extends": "eslint-protect-me-from-my-stupidity/react"
}
```

##### Node.js

```
{
  "extends": "eslint-protect-me-from-my-stupidity/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
