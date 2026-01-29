# GALA Demo Package

A simple demo GALA package for testing the dependency management system.

## Installation

```bash
gala mod add github.com/martianoff/gala_demo_pkg
```

## Usage

```gala
import "github.com/martianoff/gala_demo_pkg"

func main() {
    val result = demomath.Add(1, 2)
    println(result)
}
```

## Functions

- `Add(a Int, b Int) Int` - Returns the sum of two integers
- `Subtract(a Int, b Int) Int` - Returns the difference
- `Multiply(a Int, b Int) Int` - Returns the product
- `Max(a Int, b Int) Int` - Returns the larger value
- `Min(a Int, b Int) Int` - Returns the smaller value
- `Abs(n Int) Int` - Returns the absolute value
