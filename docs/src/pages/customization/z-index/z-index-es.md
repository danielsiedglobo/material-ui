# z-index

<p class="description">z-index is the CSS property that helps control layout by providing a third axis to arrange content.</p>

Several Material-UI components utilize `z-index`, employing a default z-index scale in Material-UI that has been designed to properly layer drawers, modals, snackbars, tooltips, and more.

[Estos valores](https://github.com/mui-org/material-ui/blob/next/packages/material-ui/src/styles/zIndex.js) comienzan con un número arbitrario, alto y lo suficientemente específico como para evitar conflictos idealmente.

- mobile stepper: 1000
- speed dial: 1050
- app bar: 1100
- drawer: 1200
- modal: 1300
- snackbar: 1400
- tooltip: 1500

Estos valores pueden ser personalizados. Customization of individual values is discouraged; should you change one, you likely need to change them all. You will find them in the theme under the [`zIndex`](/customization/default-theme/?expand-path=$.zIndex) key of the theme.
