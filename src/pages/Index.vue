<template>
  <Layout>
    <div v-for="item in news">
      <CardNoticias :news-data="item"/>
    </div>
  </Layout>
</template>

<script>
import CardNoticias from "../components/CardNoticias";
export default {
  data() {
    return {
      news: [
        {
          id: 1,
          title: "titulo1",
          body:
            "dew dew dew dw de wd we dwed we de wd  erv f  v r ef erf er fer f erfe",
          author: "Juanito Alcachofa",
          createdAt: "2020-12-03",
          updatedAt: "2020-10-23",
        },
        {
          id: 2,
          title: "titulo2",
          body:
            "dew dew dew dw de wd we dwed we de wd  erv f  v r ef erf er fer f erfe",
          author: "Juanito Alcachofa",
          createdAt: "2020-12-03",
          updatedAt: "2020-10-23",
        },
        {
          id: 3,
          title: "titulo3",
          body:
            "dew dew dew dw de wd we dwed we de wd  erv f  v r ef erf er fer f erfe",
          author: "Juanito Alcachofa",
          createdAt: "2020-12-03",
          updatedAt: "2020-10-23",
        },
        {
          id: 4,
          title: "titulo4",
          body:
            "dew dew dew dw de wd we dwed we de wd  erv f  v r ef erf er fer f erfe",
          author: "Juanito Alcachofa",
          createdAt: "2020-12-03",
          updatedAt: "2020-10-23",
        },
      ],
    };
  },
  metaInfo: {
    title: "Home!",
  },
  components: {
    CardNoticias,
  },
};
</script>
