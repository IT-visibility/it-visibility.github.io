# runUnsafeSQL

`runUnsafeSQL` is a function under the default class.

## Example
```Javascript

import Opdracht from "ctflib"

const opdracht = new Opdracht(1, "Header Tag", "Lees de header uit", 20, "Beginner", "a", "a");

let query = "Example SQL Query..";
const setup = "Database setup script";

opdracht.runUnsafeSQL(query, setup).then(data => {
    console.log(data); // Database results 
})

```

## Function arguments
1. Query that needs to be ran on the database
2. Setup SQLite commands that need to be ran (to create a database and/or data) before the query is ran.