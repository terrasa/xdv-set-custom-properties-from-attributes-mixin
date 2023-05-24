# \<@xiul/xdv-set-custom-properties-from-attributes-mixin>

Mixin to set the custom properties from html attributes.

## Installation

```bash
npm i @xiul/xdv-set-custom-properties-from-attributes-mixin
```

## Usage

```html
  <xdv-checkbox
    data-switch-bar-bg='var(--client-tertiary-9)'
  >
  </xdv-checkbox>
```

```js
xdvSetCustomProperties ('switch') 
```

The rule --switch-bar-bg  is created or modified 

```css
  --switch-bar-bg: var(--client-tertiary-9)
```