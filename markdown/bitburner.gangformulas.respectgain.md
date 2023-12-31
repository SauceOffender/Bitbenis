<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [GangFormulas](./bitburner.gangformulas.md) &gt; [respectGain](./bitburner.gangformulas.respectgain.md)

## GangFormulas.respectGain() method

Calculate respect gain per tick.

**Signature:**

```typescript
respectGain(gang: GangGenInfo, member: GangMemberInfo, task: GangTaskStats): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  gang | [GangGenInfo](./bitburner.ganggeninfo.md) | Gang info from [getGangInformation](./bitburner.gang.getganginformation.md) |
|  member | [GangMemberInfo](./bitburner.gangmemberinfo.md) | Gang info from [getMemberInformation](./bitburner.gang.getmemberinformation.md) |
|  task | [GangTaskStats](./bitburner.gangtaskstats.md) | Gang info from [getTaskStats](./bitburner.gang.gettaskstats.md) |

**Returns:**

number

The calculated respect gain.

