# Innovatia Travel Website

## CSS Structure

The CSS for this website has been modularized for better performance and maintainability. Instead of using large monolithic CSS files, we've split the styles into smaller, focused files:

### CSS Files Structure

- **css/main.css**: Main CSS file that imports all other CSS files
- **css/base.css**: Reset, variables, and base styles
- **css/layout.css**: Container and grid layout styles
- **css/navigation.css**: Navigation and menu styles
- **css/hero.css**: Hero section styles
- **css/blog.css**: Blog-specific styles
- **css/components.css**: Reusable component styles (cards, buttons, forms, etc.)
- **css/footer.css**: Footer styles
- **css/theme-toggle.css**: Theme toggle functionality styles
- **css/responsive.css**: All responsive styles

### Benefits of This Structure

1. **Faster Loading**: Only the CSS needed for each page is loaded
2. **Better Caching**: Individual CSS files can be cached separately
3. **Easier Maintenance**: Smaller files are easier to maintain and update
4. **Better Organization**: Styles are organized by function
5. **Improved Performance**: Smaller CSS files parse faster

### How to Use

Simply include the main CSS file in your HTML:

```html
<link rel="stylesheet" href="css/main.css">
```

This will automatically import all the necessary CSS files.

## Development

To modify styles:

1. Find the appropriate CSS file for the component you want to modify
2. Make your changes in that file
3. The changes will be automatically applied when the page is refreshed

## Browser Support

This CSS structure supports all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge
