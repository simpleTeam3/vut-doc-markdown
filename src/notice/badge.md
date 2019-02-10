# Badge 红点标记

### 基本
```html
/*vue*/
<template>
    <div>
        <div>
            <vut-badge value="100">
                <vut-button>新消息</vut-button>
            </vut-badge>
            <vut-badge value="100">
                <vut-button type="primary">新消息</vut-button>
            </vut-badge>
            <vut-badge value="100" :maxValue="99">
                <vut-button>新消息</vut-button>
            </vut-badge>
            <vut-badge value="new">
                <vut-button>新消息</vut-button>
            </vut-badge>
        </div>
        <div>
            <vut-badge dot>
                <vut-button>新消息</vut-button>
            </vut-badge>
            <vut-badge dot>
                <vut-button type="primary">新消息</vut-button>
            </vut-badge>
        </div>
        <div>
            <vut-badge dot>新消息</vut-badge>
            <vut-badge dot>
                <vut-button type="primary">新消息</vut-button>
            </vut-badge>
        </div>
    </div>
</template>
<script>
export default {
    data(){
        return {

        }
    }
}
</script>
<style>
    .vut-badge{
        margin: 10px 10px;
    }
</style>
```

### Attribute

属性|说明|类型|可选|默认
---|------|----|-----|-----
value| 标记显示数额| Number| --| --
maxValue| 显示最大数额,大于该数额后显示省略号| Number| --| --
type| 标记类型| String| primary| --