# Pure CSS toggle switch

## install

```
npm i toggle-switch-css
```

or

```
yarn add toggle-switch-css
```

## use

```html
<label class="toggle-switch my-toggle-switch">
    <input type="checkbox" id="toggle-switch-input" class="toggle-switch-input" />
    <label for="toggle-switch-input" class="toggle-switch-label">
        <span class="toggle-switch-ripple"></span>
    </label>
    toggle
</label>
```

default css variables

```css
.toggle-switch {
    --bar-height: 14px;
    --bar-width: 32px;
    --knob-size: 20px;
    --offset: calc(var(--knob-size) - var(--bar-height));
    --width: calc(var(--bar-width) + var(--offset));
    --motion-length: calc(((var(--bar-width) - var(--bar-height)) / 2));
    --transition-duration: 200ms;
    --transition: all var(--transition-duration) ease-in-out;
    --backgroung-color: #eee;
    --knob-color: #fff;
    --theme-color: #1a73e8;
    --box-shadow: 0 0 var(--offset) #11111180;
    --margin: 8px;
}
```

## [demo](https://magic-akari.github.io/toggle-switch)
