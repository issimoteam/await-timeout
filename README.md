![size](https://img.shields.io/bundlephobia/minzip/@sebastbake/await-timeout)
![downloads](https://img.shields.io/npm/dw/@sebastbake/await-timeout)
![npm](https://img.shields.io/npm/v/@sebastbake/await-timeout)
![GitHub](https://img.shields.io/github/license/sebastbake/await-timeout)

# await-timeout

It's literally just this:

```ts
export default function Timeout(ms: number): Promise<void> {
  return new Promise((resolve) => setTimeout(() => resolve(), ms));
}
```
