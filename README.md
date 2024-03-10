# Ring of Gyges

Ring of Gyges is a library combining existing methods of browser fingerprinting to achieve the highest possible accuracy.


# Usage

The CDN Script

```<script src="https:...."></script>```

or NPM install:

```npm i ring-of-gyges```

Create the Ring of Gyges ID:

```javascript
import { identity } from "ring-of-gyges";
```

```javascript
identity().then((result) => {
  console.log("ring-of-gyges ID: ", result.id);
  console.log("Parts its build based on", result.parts);
});
```

## Lore

In Greek mythology, the Ring of Gyges was a magical ring that granted its wearer the power of invisibility. This ring could be used to track or identify individuals without being seen, as the wearer could move about unseen while observing others