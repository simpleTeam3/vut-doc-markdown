# Checkbox 多选框

### 基本
```html
/*vue*/
<template>
    <div>
        <vut-checkbox v-model="checked1">美丽</vut-checkbox>
        <vut-checkbox v-model="checked2">世界</vut-checkbox>
        <vut-checkbox v-model="checked3">孤儿</vut-checkbox>
    </div>
</template>

<script>
export default {
    data(){
        return {
            checked1: true,
            checked2: false,
            checked3: false
        }
    }
}
</script>
```

### Attribute

属性|说明|类型|可选|默认
---|------|------|--------|-------
v-model| 绑定值| Boolean| --| --
