# Macmap

## Desc

Find the vendor information by mac address

## Installation

```bash
bash > go get -u github.com/YaoMiss/macmap
```

## Usage

```go
import (
    macmap "github.com/YaoMiss/macmap@v1.0.1"
)

m1 := macmap.Search("18:65:90:dc:c0:cb")
m2 := manuf.Search("00:ec:0a:ff:b7:27")

log.Print(m1)
log.Print(m2)
```