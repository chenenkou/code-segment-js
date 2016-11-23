# code-segment-js
代码段-javascript

## 异步GET请求
```
<!-- 一般GET -->
<a href="">点击</a>
<!-- 异步GET -->
<a class="ajax-get" href="">点击</a>
```

## 异步POST-FORM
```
<!-- submit按钮添加target-form自定义属性 -->
<!-- target-form自定义属性值对应form的类名 -->
<form method="post" class="form">
    <input type="submit" class="ajax-post" value="提交" target-form="form"/>
</form>
```

## 数据List全选
```
<!-- .confirm操作确认 -->
<!-- url自定义属性 提交的服务地址 -->
<!-- target-form自定义属性值对应列表项类名 -->
<button class="btn ajax-post confirm" url="http://localhost/" target-form="ids">批量操作</button>
<!-- .check-all全选按钮类名 -->
<input class="check-all" type="checkbox">
<!-- .ids类 全选列表项 -->
<input class="ids" type="checkbox" name="id[]" value="8">
<input class="ids" type="checkbox" name="id[]" value="9">
```