<template>
  <div class="back">
    <form id= "upload" method="post" enctype="multipart/form-data">
      画像ファイル<input type="file" name="pic">
    <br>
    <input type="submit" name="botan" value="send">
    </form>
  </div>
</template>

<style>
.back {
  margin: 10px 0;
  background-color: #aaeedd;
  height: 100vh;
}
</style>
