<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Markdown 早見表</h3>
    <table border= "1" class= "markdown_table">
      <tr>
        <th>希望の表示</th>
        <th>マークダウン</th>
      </tr>
      <tr>
        <th>コード</th>
        <th>```</th>
      </tr>
      <tr>
        <th>インライン表示</th>
        <th>`(ここに文字を記載)`</th>
      </tr>
      <tr>
        <th>強調(太字)</th>
        <th>**(ここに文字を記載)**</th>
      </tr>
      <tr>
        <th>強調(斜体)</th>
        <th>*(ここに文字を記載)*</th>
      </tr>
      <tr>
        <th>チェックボックス(チェック済)</th>
        <th>- [x] チェックボックス</th>
      </tr>
      <tr>
        <th>引用</th>
        <th>> text</th>
      </tr>
      <tr>
        <th>テーブル</th>
        <th>|  TH  |  TH  |<br>| ---- | ---- |<br>|  TD  |  TD  |<br>|  TD  |  TD  |</th>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: 'markDownList',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
  color: red;
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
  color: #42b983;
}
.markdown_table {
  margin-left: auto;
  margin-right: auto;
}
</style>