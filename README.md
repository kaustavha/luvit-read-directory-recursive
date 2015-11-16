# Luvit-read-directory-recursive AKA luvit-walk

E.g
```
local readdirRecursive = require('luvit-walk').readdirRecursive

readdirRecursive(readdir('/etc', function(k, v) print(table.concat(v, '\n')) end)
```

## Tests

Tests are run by:  

```
luvit tests/test-read-directory-recursive.lua
```
