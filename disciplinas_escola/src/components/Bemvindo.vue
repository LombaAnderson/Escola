<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Abaixo vocês poderão conferir uma lista de disciplinas que deverão ser estudadas e as datas das provas do Enem
      Por último estão as disciplinas com suas respectivas datas<br>

    
    </p>
    <h3>Disciplinas que serão estudadas</h3>
    <ul>
      <li><a href="https://www.educabras.com/ensino_medio" target="_blank" rel="noopener">Lista</a></li>
      <li><a href="https://blog.estacio.br/esta-na-midia/inscricao-enem-2021/?gclid=Cj0KCQjw7MGJBhD-ARIsAMZ0eesMGxa4ANE7sNzEPji65ERjZnjp-FriaSXJGoRaqMChkOyk8evA2RkaAqYSEALw_wcB" target="_blank" rel="noopener">Datas Enem</a></li>
    </ul>
    <h3>Datas das provas de nossa escola</h3>
    <ul>
          <h4>Datas das provas de nossa escola</h4>
          <h5>Matemática : dia 5 de Setembro </h5>
          <h5>Português : dia 6 de Setembro </h5>
          <h5>Física: dia 8 de Setembro </h5>
          <h5>Francês : dia 10 de Setembro </h5>
          <h5>Geografia : dia 11 de Setembro </h5>
          <h5>Inglês : dia 12 de Setembro </h5>
    
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'Bemvindo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #aaa;
}
</style>
