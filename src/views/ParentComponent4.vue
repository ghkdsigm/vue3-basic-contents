<template>
 <child-component @send-message="sendMessage" />
 <div>
   {{newData}}
 </div>
</template>
<script>
import ChildComponent from './ChildComponent4';
export default {
 components: {ChildComponent},
 data(){
   return{
     newData:''
   }
 },
 methods: {
   sendMessage(data) {
     this.newData = data
   }
 }
}
</script>