# Polyscope X Material Theme Integration

This guide walks you through the steps to integrate the `polyscope-x-material-theme` into your Angular application.

---

## Prerequisites

- An Angular application set up and running.
- Access to the `polyscope-x-material-theme` npm package.

---

## Billing Information

Our service is **completely free to use**! You can access all features without any cost or obligation. However, if you would like additional support or consultancy, you have the option to make a payment.

### Why Pay?
You gain access to:
- **Priority Support**: Receive dedicated assistance from our team to resolve issues or answer questions.
- **Consultancy Services**: Get expert advice and guidance tailored to your specific needs, helping you make the most out of our service.

---

For consultancy inquiries, feel free to contact us at [contact@rocketfarm](mailto:contact@rocketfarm).

---

## Steps to Integrate

### 1. Add `id="app-root"` to Your Front-End Application

Locate the root element in your application and add the `id="app-root"` attribute to it. For example:

```html
<div *ngIf="applicationNode" class="component" id="app-root">
```

    
### 2. Add the Stylesheet to `includePaths` in `angular.json`

Edit your `angular.json` file to include the `polyscope-x-material-theme` path in the `stylePreprocessorOptions` section. Here's an example:

```json
"stylePreprocessorOptions": {
  "includePaths": [
    "node_modules/polyscope-x-material-theme"
  ]
}
```

### 3. Add polyscope-x-material-theme to styles.scss
In your styles.scss file (or equivalent global styles file), import the polyscope-x-material-theme as follows:

```
@import 'polyscope-x-material-theme';
````

## Reporting Issues

If you encounter a bug or have a feature request, please open an issue in the [repository](https://github.com/RocketfarmAS/psx_material-theme). Be sure to include:

    • A clear and descriptive title.
	• Steps to reproduce the issue (if applicable).
	• Expected and actual behavior.