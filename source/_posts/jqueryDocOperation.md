---
title: jQuery 文档操作方法
date: 2019-03-16 22:28:38
tags: 
  - jQuery
---

## 添加/删除CLASS

```javascript
$("div").addClass("classOne").removeClass("classTwo");
```

## 插入HTML

### after()

```javascript
// after()	在匹配的元素之后插入内容。
$("#after").click(function () {
    $("#tbody").after(
        '<tr class="table-info">' +
        '<td scope="row">after()</td>' +
        '<td>在匹配的元素之后插入内容。</td>' +
        '</tr>'
    );
});
```

![after()](jqueryDocOperation/after.png)
