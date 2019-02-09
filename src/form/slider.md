# Slider 滑动条
数值选择滑动条

### 基本
```html
/*vue*/
<template>
    <div>
        <div class="sliderBox">
            <span>{{v1}}</span>
            <vut-slider v-model="v1"></vut-slider>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            v1: 23
        }
    }
}
</script>
<style>
.sliderBox{
    width:500px;
}
</style>
```

### Attribute

属性|说明|类型|可选|默认
---|------|------|--------|-------
v-model| 滑动选择值| Number| --| 0