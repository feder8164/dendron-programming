---
id: 46f073d8-8e53-49a0-932d-27f64ab92a03
title: Lokalna_referencja
desc: >-
  Dodaj do elementu HTML wywolanie funkcji typescript z parametrem lokalnej
  referencji za pomoca zdarzenia click
updated: 1609125354346
created: 1608691278822
---

# Angular

## Dodaj do elementu HTML wywolanie funkcji typescript z parametrem lokalnej referencji za pomoca zdarzenia click

```ts
changeFirstName(firstNameRef:HTMLInputElement) {
this.user.firstName = firstNameRef.value;
}
```
* * *
```html
<input type="text" [value]="user.firstName" ~~#firstNameRef~~>
<button ~~(click)="changeFirstName(~~firstNameRef~~)">~~Change Name</button>
```
[[ang]] [[ang.dd.html.w.element.d.ts.w.funkcja.wywolanie.parametr.d.lokalna_referencja]] 
[[html]] [[html.w.element]]
[[ts]] [[ts.w.funkcja.wywolanie.parametr]]

[[ang.dd.html.w.element.d.ts.w.funkcja.d.lokalna_referencja]]

ang.dd.html.w.element.d.ts.w.funkcja.lokalna_referencja.d.zdarzenie.click

html.element
angular.zdarzenie
angular.lokalna_referencja
ts.funkcja



