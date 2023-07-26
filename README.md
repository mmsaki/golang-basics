# golang-basics

1. Create [`/packages.go`](./packages.go) and declare package
    ```go
    package main
    ```

1. declare imports

    ```go
    package main

    import  (
        "fmt"
        "math"
    )
    ```

1. declare main function

    ```go
    package main

    import (
        "fmt"
        "math"
    )
    
    func main() {
        fmt.Printf("Now you have %g problems. \n", math.Sqrt(7))
    }
    ```

1. Run program

    ```sh
    go run packages.go
    ```
