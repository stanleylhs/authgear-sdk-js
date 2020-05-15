---
id: version-2.3.0-web.container
title: Container class
hide_title: true
original_id: web.container
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## Container class

Skygear APIs container.

<b>Signature:</b>

```typescript
export declare class Container<T extends BaseAPIClient> 
```

## Remarks

This is the base class to Skygear APIs. Consumers should use platform-specific containers instead.

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(options)](./web.container._constructor_.md) |  | Constructs a new instance of the <code>Container</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [apiClient](./web.container.apiclient.md) |  | <code>T</code> |  |
|  [classicAuth](./web.container.classicauth.md) |  | <code>AuthContainer&lt;T&gt;</code> |  |
|  [name](./web.container.name.md) |  | <code>string</code> | Unique ID for this container. |
|  [storage](./web.container.storage.md) |  | <code>ContainerStorage</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [\_configure(options)](./web.container._configure.md) |  |  |
|  [fetch(input, init)](./web.container.fetch.md) |  | <code>fetch</code> function for calling microservices. |
