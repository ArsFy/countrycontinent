# country-continent

> Try this: [github.com/RobinToubi/countries](https://github.com/RobinToubi/countries)

Get continent name from Country code, and Get Country code from continent name.

-----

## Install

```
go get github.com/ArsFy/countrycontinent@v1.2.0
```

## Use

#### Country code To Continent name

```
func CountryGetContinent(cc string) string
```

#### Continent name To Country code list

```
func ContinentGetCountry(ct string) []string
```

## Example

```go
package main

import (
    "github.com/ArsFy/countrycontinent"
)

func main(){
    countrycontinent.CountryGetContinent("HK")   // "Asia"
    countrycontinent.ContinentGetCountry("Asia")
    // [AF AM AZ BH BD BT BN KH CN CX CC CY GE HK IN ID IR IQ IL JP JO KZ KP KR KW KG LA LB MY MV MN MM NP OM PK PH QA RU SA SG LK SY TW TJ TH TR TM AE UZ VN YE]
}
```
