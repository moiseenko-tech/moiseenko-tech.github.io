+++
date = '2025-03-26T02:22:32+02:00'
draft = true
title = 'Тестовый пост'
+++
# 02-01-11-wordcount

```go
package main

import (
	"fmt"
	"os"
	"strings"
)

func wordcount(s string) int {
	return len(strings.Fields(s))
}

func main() {
	if len(os.Args) > 1 {
		fmt.Println(wordcount(os.Args[1]))
	} else {
		fmt.Println(0)
	}
}
```