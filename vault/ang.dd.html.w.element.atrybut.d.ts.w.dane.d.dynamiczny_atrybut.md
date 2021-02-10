---
id: b95fc0c4-7dfe-4b70-a477-dce29c894da6
title: Dynamiczny_atrybut
desc: >-
  Dodanie dynamicznego atrybutu do elementu atrybutu HTML za pomoca danych
  typescript
updated: 1609113491404
created: 1608690289543
---

# Angular

## Dodanie dynamicznego atrybutu do elementu atrybutu HTML za pomoca danych typescript  

```ts
~~askAboutName = false;~~
```
---
```html
<div    [title]="user.firstName" 
        ~~[hidden]="!askaboutname"~~  
        [attr.data-test]="user.isSubscribed" 
        role="presentation">
        <input type="text" [value]="user.firstName">
</div>
```
[[ang]]  [[ang.dd.html.w.element.atrybut.d.ts.w.dane.d.dynamiczny_atrybut]]
[[html]] [[html.w.element.atrybut]]
[[ts]] [[ts.w.dane]]


ang.dd.html.w.element.d.ts.w.dane.d.dynamiczny_atrybut