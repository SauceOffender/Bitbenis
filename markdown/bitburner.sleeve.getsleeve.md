<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Sleeve](./bitburner.sleeve.md) &gt; [getSleeve](./bitburner.sleeve.getsleeve.md)

## Sleeve.getSleeve() method

Get information about a sleeve.

**Signature:**

```typescript
getSleeve(sleeveNumber: number): SleevePerson;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  sleeveNumber | number | Index of the sleeve to retrieve information. |

**Returns:**

[SleevePerson](./bitburner.sleeveperson.md)

Object containing information about this sleeve.

## Remarks

RAM cost: 4 GB

Return a person object for this sleeve

storedCycles is the amount of Bonus Time in cycles, each translates to 200ms

