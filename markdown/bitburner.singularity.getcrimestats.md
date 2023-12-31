<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Singularity](./bitburner.singularity.md) &gt; [getCrimeStats](./bitburner.singularity.getcrimestats.md)

## Singularity.getCrimeStats() method

Get stats related to a crime.

**Signature:**

```typescript
getCrimeStats(crime: CrimeType | `${CrimeType}`): CrimeStats;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  crime | [CrimeType](./bitburner.crimetype.md) \| \`${[CrimeType](./bitburner.crimetype.md)<!-- -->}\` | Name of crime. |

**Returns:**

[CrimeStats](./bitburner.crimestats.md)

The stats of the crime.

## Remarks

RAM cost: 5 GB \* 16/4/1

Returns the stats of the crime.

