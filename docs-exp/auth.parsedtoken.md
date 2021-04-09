<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth](./auth.md) &gt; [ParsedToken](./auth.parsedtoken.md)

## ParsedToken interface

Interface representing a parsed ID token.

<b>Signature:</b>

```typescript
export interface ParsedToken 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [auth\_time?](./auth.parsedtoken.auth_time.md) | string | <i>(Optional)</i> Time at which authentication was performed. |
|  [exp?](./auth.parsedtoken.exp.md) | string | <i>(Optional)</i> Expiration time of the token. |
|  [firebase?](./auth.parsedtoken.firebase.md) | { 'sign\_in\_provider'?: string; 'sign\_in\_second\_factor'?: string; } | <i>(Optional)</i> Firebase specific claims, containing the provider(s) used to authenticate the user. |
|  [iat?](./auth.parsedtoken.iat.md) | string | <i>(Optional)</i> Issuance time of the token. |
|  [sub?](./auth.parsedtoken.sub.md) | string | <i>(Optional)</i> UID of the user. |
