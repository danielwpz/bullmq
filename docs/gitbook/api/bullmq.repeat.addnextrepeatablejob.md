<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Repeat](./bullmq.repeat.md) &gt; [addNextRepeatableJob](./bullmq.repeat.addnextrepeatablejob.md)

## Repeat.addNextRepeatableJob() method

<b>Signature:</b>

```typescript
addNextRepeatableJob(name: string, data: any, opts: JobsOptions, skipCheckExists?: boolean): Promise<Job<any, any, string>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  name | string |  |
|  data | any |  |
|  opts | [JobsOptions](./bullmq.jobsoptions.md) |  |
|  skipCheckExists | boolean |  |

<b>Returns:</b>

Promise&lt;[Job](./bullmq.job.md)<!-- -->&lt;any, any, string&gt;&gt;

