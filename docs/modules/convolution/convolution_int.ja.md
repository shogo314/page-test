[モジュール](../index.md) > [convolution](./index.md) > [convolution_int]()

# `convolution_int`

```
fn convolution_int(a: List[Int], b: List[Int]) raises -> List[Int]
```

畳み込みを計算する。$`a, b`$ の少なくとも一方が空配列の場合は空配列を返す。

## 制約

- $`|a| + |b| - 1 \le 2^{24}`$
- 畳み込んだ後の配列の要素が全て `Int` に収まる

## 計算量

$`n = |a| + |b|`$ として

- $`O(n \log n)`$
