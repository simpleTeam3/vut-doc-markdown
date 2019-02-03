# Select选择框

### 基本  
```html
/*vue*/
<template>
	<div class="select-box">
		<vut-select @select="handleSelect">
			<vut-option
			v-for="(o, index) in options"
			:key="index"
			:label="o.label"
			:value="o.value"
		></vut-option>
		</vut-select>
	</div>
</template>
<script>
	export default {
		data(){
			return {
				options: [
					{
						value: 1,
						label: "睡觉"
					},
					{
						value: 2,
						label: "吃饭"
					},
					{
						value: 3,
						label: "打豆豆"
					},
					{
						value: 4,
						label: "随风"
					},
					{
						value: 5,
						label: "如画"
					}
				]
			}
		},
		methods: {
			handleSelect(obj){
			}
		}
	}
</script>
<style>
.select-box{
	width: 200px;
}
</style>
```

<br/>
 
### Attributes  

#### Select

#### Option
属性 |说明| 类型| 可选| 默认
----|----|----|-----|----
label| 选项描述| String| --| --
value| 选项key, 唯一值| String, Number| --| --

### Select Events
事件名 |说明| 参数
----|----|----
select| 选中某项| 选中值