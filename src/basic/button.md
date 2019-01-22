# Button 按钮
常见的button  
<br/>
#### 基本按钮
<vut-button>默认按钮</vut-button>
<vut-button type="primary">主要按钮</vut-button>
<vut-button type="success">成功按钮</vut-button>
<vut-button type="warning">警告按钮</vut-button>
<vut-button type="error">错误按钮</vut-button>

```vue
<vut-button>默认按钮</vut-button>
<vut-button type="primary">主要按钮</vut-button>
<vut-button type="success">成功按钮</vut-button>
<vut-button type="warning">警告按钮</vut-button>
<vut-button type="error">错误按钮</vut-button>
```

#### 朴素按钮
增加plain属性  
<br/>
<vut-button plain>朴素按钮</vut-button>
<vut-button type="primary" plain>主要按钮</vut-button>
<vut-button type="success" plain>成功按钮</vut-button>
<vut-button type="warning" plain>警告按钮</vut-button>
<vut-button type="error" plain>错误按钮</vut-button>
```vue
<vut-button plain>朴素按钮</vut-button>
<vut-button type="primary" plain>主要按钮</vut-button>
<vut-button type="success" plain>成功按钮</vut-button>
<vut-button type="warning" plain>警告按钮</vut-button>
<vut-button type="error" plain>错误按钮</vut-button>
```

#### 禁选状态
增加disabled属性  
<br/>
<vut-button disabled>禁止按钮</vut-button>
<vut-button type="primary" disabled>主要按钮</vut-button>
<vut-button type="success" disabled>成功按钮</vut-button>
<vut-button type="warning" disabled>警告按钮</vut-button>
<vut-button type="error" disabled>错误按钮</vut-button>
```vue
<vut-button disabled>禁止按钮</vut-button>
<vut-button type="primary" disabled>主要按钮</vut-button>
<vut-button type="success" disabled>成功按钮</vut-button>
<vut-button type="warning" disabled>警告按钮</vut-button>
<vut-button type="error" disabled>错误按钮</vut-button>
```

#### 文字按钮
type属性设置为`text`  

<vut-button type="text">文字按钮</vut-button>
<vut-button type="text" disabled>文字禁用按钮</vut-button>


#### Attributes
<br/>

属性 |说明| 类型|  可选| 默认
---|--------------|------|--------|----------
plain|是否朴素样式|Boolean|——|false
disabled| 禁止可选| Boolean|——|false
type| 按钮类型，可选文字类型| String|`primary ``text`| ——