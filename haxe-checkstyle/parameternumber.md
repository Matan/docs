---
title: Parameter Number
toc: false
---

Checks the number of parameters of a method.

### Configuration

```json
{
    "type": "ParameterNumber",
    "props": {
        "severity": "INFO",
        "max": 7,
        "ignoreOverriddenMethods": false
    }
}
```

### `ignoreOverriddenMethods`

Ignore number of parameters for overridden methods.

{{site.data.alerts.info}} In some cases, when overriding methods from third party libraries developer will not have control over number of parameters. {{site.data.alerts.end}}