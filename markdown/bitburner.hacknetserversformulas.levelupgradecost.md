<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [HacknetServersFormulas](./bitburner.hacknetserversformulas.md) &gt; [levelUpgradeCost](./bitburner.hacknetserversformulas.levelupgradecost.md)

## HacknetServersFormulas.levelUpgradeCost() method

Calculate cost of upgrading hacknet server level.

**Signature:**

```typescript
levelUpgradeCost(startingLevel: number, extraLevels?: number, costMult?: number): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  startingLevel | number | starting level |
|  extraLevels | number | _(Optional)_ amount of level to purchase (defaults to 1) |
|  costMult | number | _(Optional)_ player cost reduction (default to 1) |

**Returns:**

number

The calculated cost.

