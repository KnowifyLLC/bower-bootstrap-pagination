
## bootstrap-bower-pagination

This is the bower repository for the pagination component of of the [angular-ui/bootstrap project](https://github.com/angular-ui/bootstrap) project.

### Usage

Include the js file into your HTML with a `<script>` tag or your preferred tool.

Use `ui-pagination-tpls.js` to use the default html templates (recommended). Alternatively, Use `ui-pagination.js` if you wish to create your own html templates.

Then, be sure to include the module as a dependency for your app:
```js
angular.module('myApp', ['ui.bootstrap.pagination']
```



And if you are using `ui-pagination-tpls.js`, be sure to additionally include the bundled html templates as dependencies:
```js
angular.module('myApp', [
  'ui.bootstrap.pagination',
  'template/pagination/pager.html',
  'template/pagination/pagination.html'
])
```

