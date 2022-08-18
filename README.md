# Primevue Sass Themes

Primevue themes as scss files, easy to customize with variables

## themes

- ✅ Bootstrap
- 🔃 Material Design
- 🔃 Saga

## usage
add this to your `style.scss` and customize the colors

```scss
@import 'primevue/resources/primevue.min.css';
@import 'primeicons/primeicons.css';

$theme-colors: (
  primary: #007bff,
  secondary: #6c757d,
  success: #28a745,
  warning: #ffc107,
  danger: #dc3545,
  info: #17a2b8,
  help: #6f42c1,
);

@import 'primevue-sass-themes/bootstrap.scss';
```