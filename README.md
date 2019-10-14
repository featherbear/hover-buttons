Hover Buttons
---

[**Demo**](https://featherbear.github.io/hover-buttons/)  

A webpage to demonstrate how button hover animations can be customised with CSS.  

Usually, the `transition: ...` property is applied to an element.  
When a property (i.e. `background-color`) is applied to an element's `:hover` selector, the property will be animated on both the `enter` and `leave` events.

We can modify this behaviour by moving where the `transition` property is applied

---

|Effect|Transition Location| 
|:-----|:------------------|
|Enter|`<element>:hover`|
|Both|`<element>`|
|Exit|`<element>:not(:hover)`|
