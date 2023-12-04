# Opdracht/challenge class

## Default export
The default export for the CTFLib is a class that needs some information prior to working.

Do not forget to change the file extension from `.js`to `.mjs` if you haven't done so.

### Example usage
```Javascript

import Opdracht from "ctflib"

const opdracht = new Opdracht(1, "Header Tag", "Lees de header uit", 20, "Beginner", "a", "a");

```

## Class arguments
1. ID
2. Challenge name
3. Challenge description
4. Points awarded
5. Difficulty
6. User ID (A random string such as in the example can be used here)
7. User token (A random string such as in the example can be used here)