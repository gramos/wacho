# Tree Monitor

Simple node script to monitor directory.


```javascript
const
    treeMonitor = require('./tree_monitor');

treeMonitor('./sync', function(dirContent, deleted, added, changed) {
    console.log('Deleted files: ' + deleted + '\nAdded Files: '
                + added + '\nChanged Files: ' + changed);
})
```
