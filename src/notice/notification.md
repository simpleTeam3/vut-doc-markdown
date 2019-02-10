# Notification提醒

### 基本
```html
/*vue*/
<template>
    <vut-button @click="notifyOne">试试</vut-button>
</template>
<script>
export default {
    methods: {
        notifyOne(){
            this.$notify({
                title: '在干嘛'
            });
        }
    }
}
</script>
```

### Attribute

属性|说明|类型|可选|默认
---|-----|----|-----|-----
