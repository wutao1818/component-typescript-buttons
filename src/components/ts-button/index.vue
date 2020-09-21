<template>
    <button style="color: orange;font-size: 24px;">我是【ts-button】</button>
</template>
<script lang="ts">
import {Vue,Component,Prop} from 'vue-property-decorator'

@Component({
    name:'co-btn'
})
export default class CoBtnComponent extends Vue{
}
</script>

