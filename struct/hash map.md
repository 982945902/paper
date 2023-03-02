## robin_hood

https://github.com/martinus/robin-hood-hashing

### unordered_set

#### benchmark
`100w emplace/count

| type |  cost(ms) |
| ---- | ---- |
| robin_hood::unordered_set | 496 |
| std::unordered_set | 1624 |

