### Clusterize.js
---
https://github.com/NeXTs/Clusterize.js

```js
var data = ['<tr></tr>', '<tr></tr>', ...];
var clusterize = new Clusterize({
  rows: data,
  scrollId: 'scrollArea',
  contentId: 'contentArea'
});

```

```
<link href="./clusterize.css" rel="stylesheet">
<script src="./clusterize.min.js"></script>

<div class="clusterize">
  <table>
    <thread>
      <tr>
        <th>Headers</th>
      </tr>
    </thread>
  </table>
  <div id="scrollArea" class="clusterize-scroll">
    <table>
      <tbody id="contentArea" class="clusterize-content">
        <tr class="clusterize-no-data">
          <td>Loading data...</td>
        </tr>
      </tbody>
    </table>
  </div>
  
```

```
```

