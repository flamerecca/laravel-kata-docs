# Fizz Buzz

`/fizzbuzz/{number}` 回傳一個包含 `number` 個元素的 json array

- 如果該元素不被三或五整除，直接回傳該數字的字串
- 如果該元素被三整除，回傳 `"Fizz"`
- 如果該元素被五整除，回傳 `"Buzz"`
- 如果該元素同時被三和五整除，回傳 `"FizzBuzz"`

## 範例

`/fizzbuzz/2` 回傳

```json
[
  "1",
  "2"
]
```

`/fizzbuzz/15` 回傳

```json
[
    "1",
    "2",
    "Fizz",
    "4",
    "Buzz",
    "Fizz",
    "7",
    "8",
    "Fizz",
    "Buzz",
    "11",
    "Fizz",
    "13",
    "14",
    "FizzBuzz"
]
```

## Fizz Buzz Woof

