---
title: Define model output schema
slug: 6.2-model-output
author: brachtma
lastModified: 2020-07-14 02:40:10
pubDate: 2020-07-14 02:40:10
categories: Consume model
description: The first step is to make sure you have all the requirements and to clone the workshop source code.
phase: 6
step: 2
---

To access the prediction, define the schema of the output created by the model. In the *Shared* project, create a new class called `ModelOutput` with the `Score` property of type `float`. This property contains the output or predicted price generated by the model.

```csharp
public class ModelOutput
{
    public float Score { get; set; }
}
```