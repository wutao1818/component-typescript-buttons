<template>
    <button style="color: red;font-size: 28px;">我是【wutao-button】按钮 - {{descText}}</button>
</template>
<script lang="ts">
import { Vue, Component, Prop } from 'vue-property-decorator'

@Component({
    name:'TsButton'
})
export default class TsButton extends Vue{
    @Prop({
	     type: String,
	     default: 'hello ts button'
    })
    descText: string;
}
</script>

