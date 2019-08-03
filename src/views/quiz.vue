<template>
  <div class="quiz">
      <Header />
      <QustionBox />
    <h1>quiz page</h1>
  </div>
</template>
<script>
import Header from '../components/Header.vue'
import QustionBox from '../components/QuestionBox.vue'

export default {
    name: 'app',
    components:{
        Header,
        QustionBox
    }
    
}
</script>

