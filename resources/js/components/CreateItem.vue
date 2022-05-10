
<template>
  <div class="recipe-box-wrapper">
    <h1>Create An Item</h1>
    <form v-on:submit.prevent="addItem" >
      <div class="row">
        <div >
          <div class="form-group">
            <label>Recipe Name:</label>
            <input type="text" class="form-control" v-model="recipe.name">
          </div>
        </div>
        </div>
        <div class="row">
          <div >
            <div class="form-group">
              <label>Recipe Ingredients:</label>
              <input type="text" class="form-control col-md-6" v-model="recipe.Ingredients" />
            </div>
          </div>
        </div>
        <div class="row">
          <div>
            <div class="form-group">
              <label>Recipe Directions:</label>
              <input type="text" class="form-control col-md-6" v-model="recipe.Directions" />
            </div>
          </div>
        </div><br />
        <div class="form-group">
          <button class="btn btn-primary">Add Item</button>
        </div>
    </form>
  </div>
</template>
<script>
  export default {
    data(){
        return{
          recipe:{}
        }
    },
    methods: {
      addItem(){
        let uri = 'http://localhost:8081/recipes';
        open = false;
        this.axios.post(uri, this.recipe).then((response) => {
          this.$router.push({name: 'DisplayItem'})
        })
    }
  }
}
</script>