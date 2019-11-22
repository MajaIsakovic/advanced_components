<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <app-quote>
          <h4>The Quote</h4>
          <p>Some quote description....</p>
        </app-quote>
      </div>
    </div>
  </div>
</template>

<script>
    import Quote from './components/Quote.vue';

    export default {
      name: 'app',
      components: {
          'app-quote': Quote
      }
  }
</script>

<style>
</style>
