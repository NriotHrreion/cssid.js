# cssid.js

## `This Repo Has Been Archived`

By NriotHrreion

## 简介

这是一个网页css在线压缩器, 可以将你的css压缩后转为base64引入网页.

## 使用

1. 在head标签中引入**cssid.js**

```html
<script src="https://cdn.jsdelivr.net/npm/cssidjs@1.0.0/cssid.min.js"></script>
```

2. 将你要引入的CSS文件路径在console台转为base64

```javascript
btoa("./css/example.css")
> "Li9jc3MvZXhhbXBsZS5jc3M="
```

3. 在head中调用cssid

```html
<script>cssId("Li9jc3MvZXhhbXBsZS5jc3M=")</script>
```

4. 完成

## 许可

[MIT](./LICENSE)
