# getFlag

`getFlag` is a function under the default class.

## Example
```Javascript

import Opdracht from "ctflib"

const opdracht = new Opdracht(1, "Header Tag", "Lees de header uit", 20, "Beginner", "a", "a");

opdracht.getFlag().then(flag => {
    console.log(flag); // flag{DIT_IS_EEN_DEBUG_FLAG}
})

```