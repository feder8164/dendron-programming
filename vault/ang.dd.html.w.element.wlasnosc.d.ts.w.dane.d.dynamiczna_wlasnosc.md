---
id: 6be8fab7-39ab-43d5-9c6b-c64bd545c3ad
title: Dynamiczna_wlasnosc
desc: >-
  Dodanie dynamicznej wlasnosci do elementu wlasnosci HTML za pomoca danych
  typescript
updated: 1608809359006
created: 1608691249023
---

# Angular

##  Dodanie dynamicznej wlasnosci do elementu wlasnosci HTML za pomoca danych typescript
```ts
askAboutName = false;
```
---
```html
<div id="test" ~~[title]="user.firstName"~~ [hidden]="!askAboutName" data-test="test" role="presentation">
    <input type="text" [value]="user.firstName">
</div>
```
[[ang]]  [[ang.dd.html.w.element.wlasnosc.d.ts.w.dane.d.dynamiczna_wlasnosc]]
[[html]] [[html.w.element.wlasnosc]]
[[ts]] [[ts.w.dane]]
