## 简单基础样式库

使用方式：

引入

``` html
<link rel="stylesheet" href="assets/css/base.css">
```

然后写上html再加上class就可以啦

### 标题样式

------

| h1. heading | Semibold 36px |
| ----------- | ------------- |
| h2. heading | Semibold 30px |
| h3. heading | Semibold 24px |
| h4. heading | Semibold 18px |
| h5. heading | Semibold 14px |
| h6. heading | Semibold 12px |

``` html
<h1>h1. heading</h1>
<h2>h2. heading</h2>
<h3>h3. heading</h3>
<h4>h4. heading</h4>
<h5>h5. heading</h5>
<h6>h6. heading</h6>
```

### 全局样式

------

全局 font-size 设置为 14px，line-height 设置为 1.428。这些属性直接赋予 元素和所有段落元素。另外，

（段落）元素还被设置了等于 1/2 行高（即 10px）的底部外边距（margin）。

### 表格

------

为任意 <table> 标签添加 .table 类可以为其赋予基本的样式 — 少量的内补（padding）和水平方向的分隔线。这种方式看起来很多余！？但是我们觉得，表格元素使用的很广泛，如果我们为其赋予默认样式可能会影响例如日历和日期选择之类的插件，所以我们选择将此样式独立出来

| #    | First Name | Last Name | Username |
| ---- | ---------- | --------- | -------- |
| 1    | Mark       | Otto      | @mdo     |
| 2    | Jacob      | Thornton  | @fat     |
| 3    | Larry      | the Bird  | @twitter |

``` html
<div class="bs-example">
    <table class="table">
      <caption>Optional table caption.</caption>
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <td>3</td>
          <td>Larry</td>
          <td>the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
```

### 表单

------

#### 按钮

Boss Button`  Boss Button`

Embossed Button`  Embossed Button`

Default Primary Info Danger Success Warning Inverse`DefaultPrimaryInfoDangerSuccessWarningInverse`

#### 输入框

``` html
<input type="text" placeholder="..." class="form-control" />
```

``` html
<!-- Error state -->
<div class="form-group has-error">
  <input class="form-control" type="text" placeholder="Error" />
</div>

<!-- Warning state -->
<div class="form-group has-warning">
  <input class="form-control" type="text" placeholder="Error" />
</div>

<!-- Success state -->
<div class="form-group has-success">
  <input class="form-control" type="text" placeholder="Error" />
</div>

<!-- Disabled state -->
<div class="form-group">
  <input class="form-control" type="text" placeholder="Disabled" disabled />
</div>
```

