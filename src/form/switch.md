# Switch开关  

### 基本  
```html
/*vue*/
<template>
	<div>
		<div class="demo-list">
			<div class="title">switch组件实例</div>
			<vut-switch v-model="switchValue" @on-change="changeSwitch" size="large"></vut-switch>
			<vut-switch v-model="switchValue" @on-change="changeSwitch"></vut-switch>
			<vut-switch v-model="switchValue" @on-change="changeSwitch" size="small"></vut-switch>
			<vut-switch disabled size="large">
				<span slot="off">禁用</span>
			</vut-switch>
			<p>
				<vut-switch @on-change="changeSwitch" on-color="#13ce66" off-color="#ff4949" size="large">
					<span slot="on">开启</span>
					<span slot="off">关闭</span>
				</vut-switch>
			</p>
		</div>
	</div>
</template>
<script>
	export default {
		data(){
			return {
				switchValue: true
			}
		},
		methods: {
			changeSwitch(value) {
			}
		}
	}
</script>
```

<br/>

属性 | 说明 | 类型 | 可选 | 默认
--- | ---- | ---- | ---- | ----
v-model | 绑定值 | String, Number, Boolean | -- | --
size | 规格大小 | String | large, small | normal
on-color | 开启时颜色 | String | -- | #2D8CF0
off-color | 关闭时颜色 | String | -- | #CCCCCC