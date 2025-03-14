---
id: selective-disclosure.icredentialsforsdr
title: ICredentialsForSdr interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ICredentialsForSdr interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

The credentials that make up a response of a Selective Disclosure

<b>Signature:</b>

```typescript
export interface ICredentialsForSdr extends ICredentialRequestInput
```

<b>Extends:</b> [ICredentialRequestInput](./selective-disclosure.icredentialrequestinput.md)

## Remarks

See [Selective Disclosure Request](https://github.com/uport-project/specs/blob/develop/messages/sharereq.md)

## Properties

| Property                                                                | Type                                                                          | Description          |
| ----------------------------------------------------------------------- | ----------------------------------------------------------------------------- | -------------------- |
| [credentials](./selective-disclosure.icredentialsforsdr.credentials.md) | [UniqueVerifiableCredential](./data-store.uniqueverifiablecredential.md) \[\] | <b><i>(BETA)</i></b> |
