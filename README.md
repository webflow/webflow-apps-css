# Webflow Apps CSS

CSS variables for building Webflow apps that look native in Designer.

Use these tokens for color, typography, and shadows so your UI matches Webflow. Values update automatically from the user’s **Appearance** settings.

## Usage

Include **one** stylesheet (the others are reference so you can see how tokens look in each theme.)

```html
<link rel="stylesheet" href="webflow-variables.css" />
```

Then use the variables in your CSS:

```css
.panel {
  background: var(--background1);
  color: var(--text1);
  border: 1px solid var(--border1);
  font-family: var(--font-stack);
  font-size: var(--font-size-large);
}
```



## Themes (reference)


| File                        | Theme          |
| --------------------------- | -------------- |
| `webflow-light.css`         | light          |
| `webflow-dark-default.css`  | dark           |
| `webflow-dark-brighter.css` | dark brighter |
| `webflow-dark-darker.css`   | dark darker   |




## Design

The [Webflow App UI Kit](https://www.figma.com/community/file/1680257493386966043) on Figma includes these variables and matching components.
