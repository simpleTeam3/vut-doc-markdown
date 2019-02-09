# Radio单选框  
在一组备选项中进行单选

### 基本  
```html
/*vue*/
<template>
    <div>
        <vut-radio v-model="city" label="1">深圳</vut-radio>
        <vut-radio v-model="city" label="2">广州</vut-radio>
        <vut-radio v-model="city" label="3">上海</vut-radio>
        <vut-radio v-model="city" label="4">北京</vut-radio>
    </div>
</template>
<script>
export default {
    data(){
        return {
            city : "1"
        }
    }
}
</script>
```
<br/>

### Attribute

属性|说明|类型|可选|默认
---|------|------|--------|-------
v-model | 绑定值 | String, Number, Boolean | -- | --