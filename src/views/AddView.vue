<template>
  <div class="addView">
    <form class="form-add">
      <div class="title">
        <label class="label-add" for="title">Title</label><br>
        <input class="input-add" type="text" id="title" name="title"><br>
      </div>
      <div class="desc">
      <label class="label-add" for="desc">Description</label><br>
      <input class="input-add" type="text" id="desc" name="desc">
      </div>
      <button @submit.prevent class="button-add" type="submit">Submit</button>
    </form>
  </div>
</template>

<style>

.form-add {
  justify-content: flex-start;
  align-items: flex-start;
  margin-top: 0.5rem;
}

.title {
  margin: 3px;
}

.desc {
  margin: 3px;
}

 .input-add {
  border-radius: 5px;
 }

 .label-add {
  font-size: 1rem;
 }

 .button-add {
  background-color: rgb(12, 226, 144);
  width: 4rem;
  height: 2rem;
  border-style: none;
  border-radius: 5px;
 }

</style>
