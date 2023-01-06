# Quinetessential-Go
Another quine, this time in Go

```
package main

import "fmt"

func main() {
	s := "package main\n\nimport \"fmt\"\n\nfunc main() {\n\ts := %#v\n\tfmt.Printf(s, s)\n}\n"
	fmt.Printf(s, s)
}

```


###### Enjoy your day.

