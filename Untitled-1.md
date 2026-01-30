<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.4.0/Chart.min.js"></script>
I've downloaded Chart.js locally and updated the script tag to reference the local file:

1. **Downloaded**: [`chart.min.js`](chart.min.js) - Chart.js v2.4.0 (local copy)
2. **Created**: [`chart-example.html`](chart-example.html) - HTML file with local Chart.js reference

The updated script tag now uses:
```html
<script src="chart.min.js"></script>
```

Instead of the CDN version:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.4.0/Chart.min.js"></script>
```

The HTML file includes a sample bar chart implementation using the local Chart.js library.
