# Deprecated in favour of [issimoteam/await-timeout](https://github.com/issimoteam/await-timeout)

It's setTimout but you can await it.

[![size](https://img.shields.io/bundlephobia/minzip/@sebastbake/await-timeout)](https://bundlephobia.com/result?p=@sebastbake/await-timeout)
[![downloads](https://img.shields.io/npm/dw/@sebastbake/await-timeout)](https://www.npmjs.com/package/@sebastbake/await-timeout)
[![npm](https://img.shields.io/npm/v/@sebastbake/await-timeout)](https://www.npmjs.com/package/@sebastbake/await-timeout)
[![GitHub](https://img.shields.io/github/license/sebastbake/await-timeout)](https://github.com/SebastBake/await-timeout)

# await-timeout

It's literally just this:

```ts
export default function Timeout(ms: number): Promise<void> {
  return new Promise((resolve) => setTimeout(() => resolve(), ms));
}
```
