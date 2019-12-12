# GoAdmin Official Themes

- [adminlte](https://github.com/glvd/themes/tree/master/adminlte)
- [sword](https://github.com/glvd/themes/tree/master/sword)

## How to use

- Import the theme
- Set in the global configuration of GoAdmin

```go

package main

import (
	...
	_ "github.com/glvd/themes/adminlte"
	...
)

func main()  {
	
	...
	
	cfg := config.Config{
    		...
    		
    		Theme: "adminlte",
    		
    		...
    	}
	
	...
 
}

```

## How to modify and make it work

Use the Makefile under each theme directory.