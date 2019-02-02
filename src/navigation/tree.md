# 树  

### 基本

```html
/*vue*/
<template>
	<div>
		<vut-button>试试括号</vut-button>
		<vut-button>试试</vut-button>
		<vut-tree :data="tree"></vut-tree>
	</div>
</template>

<script>
export default {
	data(){
		return {
			tree: [
				{
					label: '一级1',
					children: [{
						label: '二级1-1',
						children: [
							{ label: '三级1-1-1' },
							{ label: '三级1-1-2' }
						]
					},{
						label: '二级1-2'
					}]
				},{
					label: '一级2'
				}
			],
		}
	}
}
</script>
```

### Attributes  

#### Tree  
