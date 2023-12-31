<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Singularity](./bitburner.singularity.md) &gt; [getCompanyPositionInfo](./bitburner.singularity.getcompanypositioninfo.md)

## Singularity.getCompanyPositionInfo() method

Get Requirements for Company Position.

**Signature:**

```typescript
getCompanyPositionInfo(
    companyName: CompanyName | `${CompanyName}`,
    positionName: JobName | `${JobName}`,
  ): CompanyPositionInfo;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  companyName | [CompanyName](./bitburner.companyname.md) \| \`${[CompanyName](./bitburner.companyname.md)<!-- -->}\` | Name of company to get the requirements for. Must be an exact match. |
|  positionName | [JobName](./bitburner.jobname.md) \| \`${[JobName](./bitburner.jobname.md)<!-- -->}\` | Name of position to get the requirements for. Must be an exact match. |

**Returns:**

[CompanyPositionInfo](./bitburner.companypositioninfo.md)

CompanyPositionInfo object.

## Remarks

RAM cost: 2 GB \* 16/4/1

This function will return an object that contains the requirements for a specific position at a specific country.

## Example


```js
const companyName = "ECorp";
const position = "Chief Executive Officer";

let requirements = ns.singularity.getCompanyPositionInfo(companyName, position);
```

