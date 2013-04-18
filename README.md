# Raygun4js

Raygun.io plugin for JavaScript

## Getting Started
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/MindscapeHQ/raygun4js/master/dist/raygun.min.js
[max]: https://raw.github.com/MindscapeHQ/raygun4js/master/dist/raygun.js

In your web page:

```html
<script src="dist/raygun.min.js"></script>
<script>
  Raygun.init('yourApiKey');
</script>
```

To submit manual errors:

```
try {
  // your code
}
catch(e) {
  Raygun.send(e);
}
```

To attach the window.onerror handler call:

```html
<script src="dist/raygun.min.js"></script>
<script>
  Raygun.init('yourApiKey').attach();
</script>
```

If you need to detach it:

```
Raygun.detach();
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

## Release History
_(Nothing yet)_
