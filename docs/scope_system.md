# Scope System
Bait has the following scopes:
- [Package](#package-scope)
- [File](#file-scope)
- [Block](#block-scope)

## Simplified Package Structure
```
my_pkg/
|-- a.bt
`-- b.bt
```

```bait
// a.bt
package my_pkg

import strings

struct ObjA {}

fun foo() {
    myvar := true
    if myvar {
        // ...
    }
    // ...
}

// ...
```

```bait
// b.bt
package my_pkg

import other

const PART_OF_B := 1

// ...
```

## Package Scope
TODO

## File Scope
TODO

## Block Scope
TODO
