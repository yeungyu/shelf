### 数字转16进制

```js
function getHexNumber(number) {
    return (+number).toString(16).padStart(2, '0'); // 不足2位填充0
}
```

