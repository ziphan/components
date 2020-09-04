用于查询条件的多行输入，输入多行数据后将返回一个由逗号分隔的字符串

多行数据 | 返回值
-- | --
ABC<br>DEF<br>GHI| ABC,DEF,GHI

```vue
<template>
  <multiple-input v-model="data"></multiple-input>
</template>
<script>
  import MultipleInput from "@/components";
  export default {
    data(){
      return {
        data:''
      }
    },
    components: {
      MultipleInput,
    }
  }
</script>
```
