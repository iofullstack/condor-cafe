# PROJECT CONDOR CAFÉ

## Module condor-db
### Usage
```javascript
const setupDB = require('condor-db')

setupDB(config).then(db => {
  const { Table } = db
}).catch(err => console.error(err))
```
