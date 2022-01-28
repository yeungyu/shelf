## 动态增加非行内css

```js
const style = document.createElement('style');
document.head.appendChild(style);
// 需要先append才有sheet
style.sheet.insertRule('.ProseMirror p br,.ProseMirror blockquote br{display:block;content:"";height:16px;}', 0);
```

