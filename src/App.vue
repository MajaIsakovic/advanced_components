<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <button class="btn btn-danger" @click="selectedComponent = 'appQuote'">Quote</button>
        <button class="btn btn-success" @click="selectedComponent = 'appAuthor'">Author</button>
        <button class="btn btn-info" @click="selectedComponent = 'appNew'">New Quote</button>
        <br>
        <!-- <p>{{ selectedComponent }}</p> -->
        <keep-alive>
            <component :is="selectedComponent"></component>
        </keep-alive>
        <!-- <app-quote>
          <h4 slot="title">The Quote</h4>
          <p slot="content">Some quote description....</p>
        </app-quote> -->
      </div>
    </div>
  </div>
</template>

<script>
    import Quote from './components/Quote.vue';
    import Author from './components/Author.vue';
    import NewQoute from './components/New.vue';

    export default {
      name: 'app',
      data: function(){
        return{
          quoteTitle: 'The Quote',
          selectedComponent: 'appQuote'
        }
      },
      components: {
          appQuote: Quote,
          appAuthor: Author,
          appNew: NewQoute
      }
  }
</script>

<style>
</style>
