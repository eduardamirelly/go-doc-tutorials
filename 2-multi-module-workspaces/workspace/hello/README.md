## Instructions

- Clone
```
git clone https://go.googlesource.com/example
```

- New File `int.go`
```go
package reverse

import "strconv"

// Int returns the decimal reversal of the integer i.
func Int(i int) int {
    i, _ = strconv.Atoi(String(strconv.Itoa(i)))
    return i
}
```