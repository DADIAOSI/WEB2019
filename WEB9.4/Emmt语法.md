# Child: > 子元素
div>ul>li
``` 
    <div>
        <ul>
            <li></li>
        </ul>
    </div>
```
# Sibling: + 兄弟元素
div+p+bq
```
    <div></div>
    <p></p>
    <blockquote></blockquote>
```
# Climb-up: ^ 返回上层
div+div>p>span+em^bq
```
    <div></div>
    <div>
        <p><span></span><em></em></p>
        <blockquote></blockquote>
    </div>
```
# Multiplication: * 乘法
ul>li*5
```
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
```
