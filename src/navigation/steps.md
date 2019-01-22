# 步骤条

#### 基本

```html
/*vue*/
<template>
	<div>
		<vut-steps :active-step="step">
			<vut-step title="小白"></vut-step>
			<vut-step title="菜鸟"></vut-step>
			<vut-step title="熟手"></vut-step>
		</vut-steps>
		<vut-button @click="nextStep">下一步</vut-button>
	</div>
</template>
<script>
export default {
    data(){
        return {
            step: 0
        }
    },
    methods: {
        nextStep(){
			console.log("1");
            ++this.step > 2 && (this.step = 0);
        }
    }
}
</script>
```