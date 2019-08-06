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

### 使用checkboxGroup
```html
<template>
    <div>
        <vut-checkbox-group v-model="most">
            <vut-checkbox label="life">生活</vut-checkbox>
            <vut-checkbox label="cause">因你</vut-checkbox>
            <vut-checkbox label="fire">而火热</vut-checkbox>
        </vut-checkbox-group>
    </div>
</template>

<script>
export default {
    data(){
        return {
            most: []
        }
    }
}
</script>
```

### Attribute
##### checkbox
属性|说明|类型|可选|默认
---|------|------|--------|-------
v-model| 绑定值| Boolean| --| --

##### checkboxGroup
属性|说明|类型|可选|默认
---|------|------|--------|-------
v-model| 绑定值| Array| --| --