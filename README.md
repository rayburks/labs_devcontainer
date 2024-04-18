

# Azure Functions

## host.conf

v1 or v2

related for each function app.

### Overwride host.conf

**Environment Variable which starts with AzureFunctionsJobHost__**
For instance: AzureFunctionsJobHost__logging__applicationInsights__samplingSettings__isEnabled":"false"

### extensionBundle

```
{
    "version": "2.0",
    "extensionBundle": {
        "id": "Microsoft.Azure.Functions.ExtensionBundle",
        "version": "[4.0.0, 5.0.0)"
    }
}
```

### Logging

- ApplicationInsights und Console mit dabei

```
"logging": {
    "fileLoggingMode": "debugOnly",
    "logLevel": {
      "Function.MyFunction": "Information",
      "default": "None"
    },
    "console": {
        ...
    },
    "applicationInsights": {
        ...
    }
}
```

