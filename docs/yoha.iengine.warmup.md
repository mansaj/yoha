<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [yoha](./yoha.md) &gt; [IEngine](./yoha.iengine.md) &gt; [Warmup](./yoha.iengine.warmup.md)

## IEngine.Warmup() method

Prepares and optimizes the engine.

<b>Signature:</b>

```typescript
Warmup(): Promise<IWarmupResult>;
```
<b>Returns:</b>

Promise&lt;[IWarmupResult](./yoha.iwarmupresult.md)<!-- -->&gt;

Promise that resolves once warmup is complete with estimates about the performance that the engine can provide.

## Remarks

- Performs some dry runs to warm up the engine and to find optimal setup.

- Requires that [IEngine.Configure()](./yoha.iengine.configure.md) was called already.

