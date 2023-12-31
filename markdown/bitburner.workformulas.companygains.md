<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [WorkFormulas](./bitburner.workformulas.md) &gt; [companyGains](./bitburner.workformulas.companygains.md)

## WorkFormulas.companyGains() method

**Signature:**

```typescript
companyGains(
    person: Person,
    companyName: CompanyName | `${CompanyName}`,
    workType: JobName | `${JobName}`,
    favor: number,
  ): WorkStats;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  person | [Person](./bitburner.person.md) |  |
|  companyName | [CompanyName](./bitburner.companyname.md) \| \`${[CompanyName](./bitburner.companyname.md)<!-- -->}\` |  |
|  workType | [JobName](./bitburner.jobname.md) \| \`${[JobName](./bitburner.jobname.md)<!-- -->}\` |  |
|  favor | number |  |

**Returns:**

[WorkStats](./bitburner.workstats.md)

The WorkStats applied every game cycle (200ms) by performing the specified company work.

