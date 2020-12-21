It's setTimout but you can await it.

[![size](https://img.shields.io/bundlephobia/minzip/@issimo/await-timeout)](https://bundlephobia.com/result?p=@issimo/await-timeout)
[![downloads](https://img.shields.io/npm/dw/@issimo/await-timeout)](https://www.npmjs.com/package/@issimo/await-timeout)
[![npm](https://img.shields.io/npm/v/@issimo/await-timeout)](https://www.npmjs.com/package/@issimo/await-timeout)
[![GitHub](https://img.shields.io/github/license/issimoteam/await-timeout)](https://github.com/issimoteam/await-timeout)

# await-timeout

It's literally just this:

```ts
export default function Timeout(ms: number): Promise<void> {
  return new Promise((resolve) => setTimeout(() => resolve(), ms));
}
```
