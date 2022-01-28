# HtmlTableSort.js
Dynamic sort an HTML table on header click in pure javascript.

- Author  : @r1d
- Version : 1.0 
- Date    : 2022-01-12
- Example : [https://r1d.github.io/htmlTableSort.js/](https://r1d.github.io/htmlTableSort.js/)

Usage : 

```
<script src="src/htmltablesort.js"></script>

window.onload = function(){
    HtmlTableSort.init('id-table');
    };
```

Options :

- use attribute data-sort="asc" or "desc" on <th> header to define the column sorted at start
- use attribute data-sort="0" on <th> header to disallow sorting on column
- use attribute data-sort-value="value" on <td> cell for special sorting (for dates, ...)
