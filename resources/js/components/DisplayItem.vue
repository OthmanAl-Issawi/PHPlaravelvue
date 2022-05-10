
<style scoped>
.recipeview-box-wrapper {
    margin: 20px 15%;
}
#index-view {
    height: 95px;
    overflow: auto;
    margin-bottom: 5px;
    border: 5px solid #084C61;
    border-bottom: 10px solid #084C61;
    border-top: 10px solid #084C61;
    border-radius: 10px;
}
#index-view .index-view-item {
    padding: 7px;
    cursor: pointer;
}
#index-view .index-view-item:nth-child(odd) {
    background: #084C61;
    color: #F46036;
}
.recipeview-title, h4, .index-view-item, .dialog-box {
    font-family: Fugaz One;
}
.recipeview-view .recipeview-title {
    background: #084C61;
    padding: 10px;
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
}
.recipeview-view .recipeview-title div:first-of-type {
    margin-right: 10px;
    font-size: 30px;
    font-weight: bold;
}
.recipeview-view .recipeview-title .title-row {
    display: inline-block;
}
.recipeview-view .recipeview-title .title-row {
    display: inline-block;
}
.recipeview-title, h4, .index-view-item, .dialog-box {
    font-family: Fugaz One;
}
.recipeview-view .recipeview-body {
    background: #481D24;
    height: 330px;
    overflow-y: scroll;
    padding: 0 10px;
    font-family: Montserrat;
}
.recipeview-view .list {
    max-width: 600px;
}
ul {
    display: block;
    list-style-type: disc;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
}
ol {
    display: block;
    list-style-type: decimal;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
}
ol {
    list-style-type: decimal;
}
.add-button {
    background: #084C61;
    border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
    padding: 5px;
}
.dialog-box {
    text-align: center;
    position: fixed;
    width: 500px;
    min-width: 300px;
    top: 50%;
    left: 50%;
    margin-left: -250px;
    margin-top: -200px;
    box-shadow: 3px 3px 10px black;
    border-radius: 15px;
    background: #616196;
    z-index: 1000;
}
 .dialog-wrap {
    box-shadow: 2px 10px 10px 5000px rgb(0 0 0 / 60%) !important;
} 
.recipeview-title, h4, .index-view-item, .dialog-box {
    font-family: Fugaz One;
}
.fa {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.unstyle-button, .dialog-box .corner-close, .dialog-box button, .recipeview-view .recipeview-title button, .add-button button {
    background: none;
    border: none;
    outline: none;
    font-size: 32px;
    color: #481D24;
}
button {
    appearance: auto;
    writing-mode: horizontal-tb !important;
    text-rendering: auto;
    color: -internal-light-dark(black, white);
    letter-spacing: normal;
    word-spacing: normal;
    line-height: normal;
    text-transform: none;
    text-indent: 0px;
    text-shadow: none;
    display: inline-block;
    text-align: center;
    align-items: flex-start;
    cursor: default;
    box-sizing: border-box;
    background-color: -internal-light-dark(rgb(239, 239, 239), rgb(59, 59, 59));
    margin: 0em;
    padding: 1px 6px;
    border-width: 2px;
    border-style: outset;
    border-color: -internal-light-dark(rgb(118, 118, 118), rgb(133, 133, 133));
    border-image: initial;
}
.dialog-box .corner-close {
    font-size: 24px !important;
    color: #042732;
    position: absolute;
    top: 5px;
    right: 5px;
}
.unstyle-button, .dialog-box .corner-close, .dialog-box button, .recipeview-view .recipeview-title button, .add-button button {
    background: none;
    border: none;
    outline: none;
    font-size: 32px;
    color: #481D24;
}
.heading {
    font-size: 40px;
    text-align: center;
    margin-bottom: 20px;
    font-family: Sonsie One;
}
.heading div, .heading i {
    display: inline-block;
    margin-right: 15px;
}
.fa {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
div {
    display: block;
}
li {
    display: list-item;
    text-align: -webkit-match-parent;
}
ul {
    list-style-type: disc;
}
.unstyle-button:hover, .dialog-box .corner-close:hover, .dialog-box button:hover, .recipeview-view .recipeview-title button:hover, .add-button button:hover {
    color: #F46036;
}
/* ::marker {
    unicode-bidi: isolate;
    font-variant-numeric: tabular-nums;
    text-transform: none;
    text-indent: 0px !important;
    text-align: start !important;
    text-align-last: start !important;
} */
.dialog-box .corner-close {
    font-size: 24px !important;
    color: #042732;
    position: absolute;
    top: 5px;
    right: 5px;
}
.unstyle-button, .dialog-box .corner-close, .dialog-box button, .recipe-view .recipe-title button, .add-button button {
    background: none;
    border: none;
    outline: none;
    font-size: 32px;
    color: #481D24;
}
.dialog-box button {
    font-family: Fugaz One;
    font-size: 15px;
    margin-right: 8px;
    background: #063a49;
    border-radius: 5px;
}
.dialog-box textarea {
    margin-bottom: 10px;
    min-width: 300px;
    min-height: 60px;
    resize: vertical;
    color: #042732;
    font-weight: bold;
    font-size: 13px;
    overflow: auto;
}
</style>

<template>
    <div class="recipeview-box-wrapper" >
         <div class="heading">
           <i class="fa-solid fa-champagne-glasses"></i>
         <div>Recipe Box</div>
       </div>
    <div class="outer">
   <div v-if="open" class="modal">
     <div class="dialog-box dialog-wrap" id="editTodoItemModal">
       <div class="dialog-box">
      <div >
          <button class="corner-close" @click="open = false">Close</button>
            <div class="recipeview-box-wrapper">
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
              <textarea type="text" class="form-control col-md-6" v-model="recipe.Ingredients" />
            </div>
          </div>
        </div>
        <div class="row">
          <div>
            <div class="form-group">
              <label>Recipe Directions:</label>
              <textarea type="text" class="form-control col-md-6" v-model="recipe.Directions" />
            </div>
          </div>
        </div><br />
        <div class="form-group">
          <button v-on:click="addItem()" @click="open = false" class="btn btn-primary">Add Item</button>
        </div>
    </form>
  </div>
      </div>
       </div>
        </div>
    
  </div>

<div class="outer">
   <div v-if="openEdit" class="modal">
     <div class="dialog-box dialog-wrap" id="editTodoItemModal">
       <div class="dialog-box">
      <div class="recipeview-box-wrapper">
           <button class="corner-close" @click="openEdit = false">Close</button>
        <h1>Update Item</h1>
        <div class="row">
          <div class="col-md-10"></div>
        </div>

        <form v-on:submit.prevent="updateItem">
            <div class="form-group">
                <label>Recipe Name</label>
                <input type="text" class="form-control" v-model="recipe.name">
            </div>

            <div class="form-group">
                <label name="product_price">Item Price</label>
                <textarea type="text" class="form-control col-md-6" v-model="recipe.Ingredients" />
            </div>
<div class="form-group">
                <label name="product_price">Item Directions</label>
                <textarea type="text" class="form-control col-md-6" v-model="recipe.Directions" />
            </div>
            <div class="form-group">
                <button v-on:click="updateItem()" @click="openEdit = false" class="btn btn-primary">Update</button>
            </div>
        </form>
    </div>
       </div>
     </div>
   </div>
   </div>

<div id="index-view">
    <div class="index-view-item" v-for="(recipeview,id) in getTextSearch('')" :key="id">
       <div  @click.prevent="ViewForm(recipeview)">
           {{ recipeview.name }}
       </div>
    </div>
</div>

        <div>
          <div class="recipeview-view">
           <div class="recipeview-title"> 
            <div class="recipeview-view-name title-row">Garlic Chicken</div>
            <div class="title-row">
                 <button v-on:click="ChakDelete(recipeview.id)"><i class="fa-solid fa-trash-can"></i></button>
                 <button v-on:click="getItem()" @click="openEdit = true"><i class="fa-solid fa-pen-to-square"></i></button>
            </div>
           </div>
           <div class="recipeview-body">
            <h4>Ingredients:</h4>
            <ul class="ingredient list"  >
               <li v-for="(str,id) in (recipeview.Ingredients.split('\\'))" :key="id">{{ str}}</li>  
            </ul>
            <h4>Directions:</h4>
             <ol class="ingredient list" >
                   <li v-for="(str,id) in (recipeview.Directions.split('\\'))" :key="id">{{ str}}</li>  
             </ol>
           </div>
          </div>
        </div>
        <div class="add-button">
         <button @click="open = true"><i class="fa-solid fa-circle-plus"></i></button>
        </div>
    </div>
</div>

</template>

<script>
import CreateItem from './CreateItem.vue';
    export default {
        components:{
CreateItem,
        },
        data(){
            return{
                recipes: [],
                recipeview:{},
                recipe:{},
                myResult: '',
                open: false,
                openEdit: false,
            }
        },

        created: function()
        {
            this.fetchItems();
        },

        methods: {
             splitedList(row){               
              return (row !== null)?row.split('\\'):'';
        },
              ViewForm(recipeview) {
              this.recipeview=recipeview;
            },
            showEditTodoForm() {
                $('#editTodoItemModal').modal('hide');
            },
            fetchItems()
            {
              let uri = 'http://localhost:8081/recipes';
              this.axios.get(uri).then((response) => {
                  this.recipes = response.data;
                  this.recipeview=Object.keys(this.recipeview).length?this.recipeview:response.data[0];
              });
            },
            ChakDelete(id)
            {
              if (confirm('Are you sure you want to delete this record?')) 
              {
                    this.deleteItem(id);
               }
             
            },
            deleteItem(id)
            {
              let uri = `http://localhost:8081/recipes/${id}`;
              this.axios.delete(uri).then((response)=>{ this.fetchItems();});
            },
            addItem(){
        let uri = 'http://localhost:8081/recipes';
       
        this.axios.post(uri, this.recipe).then((response) => {
         this.fetchItems();
        })
         this.recipe={};
         this.$forceUpdate();
    },getItem()
            {
              let uri = `http://localhost:8081/recipes/${this.recipeview.id}/edit`;
                this.axios.get(uri).then((response) => {
                    this.recipe = response.data;
                });
            },

            updateItem()
            {
              let uri = 'http://localhost:8081/recipes/'+this.recipe.id;
                this.axios.put(uri, this.recipe).then((response) => {
                  this.fetchItems();
                  this.recipeview=this.recipe;
                });
            },getTextSearch: function(textSearch) {

        this.filteredResources= this.recipes

        return this.filteredResources.filter(item => {
            return item.name.toLowerCase().includes(textSearch);
        });

    }
        }
    }
</script>