###tab标签
```
<div class="tab">
    <ul class="fn-clear">
        <li class="current">
            <a href="#">Tab标题1</a>
        </li>
        <li>
            <a href="#">Tab标题2</a>
        </li>
        <li>
            <a href="#">Tab标题3</a>
        </li>
    </ul>
</div>
```
###主标题
```
<h2 class="title">字体最大的标题字</h2>
```
###主标题
```
<h2 class="title">字体最大的标题字</h2>
```
### 子标题
```
<h3 class="subtitle">副标题字体字号</h3>
```
###表单结构和文本框
```
<div class="form">
    <dl>
        <dt>选择厂商
        </dt>
        <dd>
            <input type="text" placeholder="水印" /><span class="error">＊商品来源：对于经销商发布的商品，新增一个商品来源，开放平台。不给经销商展示，系统写死。</span>
        </dd>
    </dl>
    <dl>
        <dt>覆盖城市
        </dt>
        <dd>
            <input class="error" type="text" value="＊输入框错误提示" /><span class="error">＊商品来源：对于经销商发布的商品，新增一个商品来源，开放平台。不给经销商展示，系统写死。</span>
        </dd>
    </dl>
    <dl>
        <dt>公司紧急<br />
            联系人手机
        </dt>
        <dd>
            <input type="text" value="禁用" disabled="disabled" />
        </dd>
    </dl>
</div>
```
###复选框
```
<label class="checkbox"><i></i><span>未选中</span></label>
<label class="checkbox checked"><i></i><span>选中</span></label>
<label class="checkbox disabled"><i></i><span>禁用</span></label>
<label class="checkbox checked disabled"><i></i><span>禁用</span></label>
如果是一组复选框，外面套一层<div class="group">给彼此增加间距
```
###单选框
```
<label class="radio" data-group="xx" data-value="1"><i></i><span>未选中</span></label>
<label data-group="xx" class="radio checked" data-value="2"><i></i><span>选中</span></label>
<label class="radio disabled" data-group="xx" data-value="1"><i></i><span>禁用</span></label>
<label data-group="xx" class="radio checked disabled" data-value="2"><i></i><span>禁用</span></label>
如果是一组单选框，外面套一层<div class="group">给彼此增加间距
```
