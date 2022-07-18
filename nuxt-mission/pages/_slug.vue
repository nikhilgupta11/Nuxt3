<!-- <template>
  <div>
    <h1>Hello this is dynamic page created by Slug.</h1>
    <h1>Dynamic Route:-{{ $route.params.slug }}</h1>
    <button v-on:click="getdata">api calling</button>
    <h1>{{ data }}</h1>
  </div>
</template>

<script>
export default {
  name: "DynamicPage",
  data() {
    return {
      data: [],
    };
  },

  methods: {
    getdata() {
      const data = fetch(`https://api.nuxtjs.dev/planets/${params.slug}`).then(
        (res) => {
          this.data = res.json();
          // console.log(res.json());
        }
      );
      return {
        data,
      };
    },
  },
};
</script> -->
