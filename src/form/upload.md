# Upload上传
上传图片或文件组件

### 基本
```html
/*vue*/
<template>
    <vut-upload 
        :multiple="true"
        action=""
        :on-success="uploadSuc"
    >
        <vut-button>点击上传</vut-button>
    </vut-upload>
</template>

<script>
export default {
    methods: {
        uploadSuc(){
            console.log("上传成功啦");
        }
    }
}
</script>
```

### Attribute

属性|说明|类型|可选|默认
---|-----|-----|------|-----
multiple| 多个上传 | Boolean | false, true | true
action| 上传文件地址| String| --| --

### Events
属性|说明|类型|可选|默认
---|-----|-----|------|-----
on-success| 上传成功后回到函数| Function| --| --