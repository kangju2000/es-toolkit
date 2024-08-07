# xor

计算两个数组之间的对称差异。

对称差异是指在任一数组中存在，但不在它们的交集中的元素集合。

## 签名

```typescript
function xor<T>(arr1: T[], arr2: T[]): T[];
```

### 参数

- `arr1` (`T[]`): 第一个数组。
- `arr2` (`T[]`): 第二个数组。

### 返回值

(`T[]`): 包含在 `arr1` 或 `arr2` 中存在但不同时存在于两者中的元素的数组。

## 示例

```typescript
// 返回 [1, 2, 5, 6]
xor([1, 2, 3, 4], [3, 4, 5, 6]);

// 返回 ['a', 'c']
xor(['a', 'b'], ['b', 'c']);
```
