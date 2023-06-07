# Stanford Identity Guide Color Palette

Source: https://identity.stanford.edu/design-elements/color/

## How to use in your project

1. Create a .npmrc file in the root of your project with the following line in it:
```
@stanford-sis:registry=https://npm.pkg.github.com
```

2. Install with NPM
```bash
npm install stanford-sis/stanford-identity-guide-sass
```

3. Import SCSS files into your JS components or your SCSS stylesheets

      JavaScript
      ```javascript
      import '../node_modules/@stanford-sis/stanford-identity-guide-sass/src/_palette.scss'
      ```

      SCSS
      ```scss
      @import '../node_modules/@stanford-sis/stanford-identity-guide-sass/src/palette';
      ```
