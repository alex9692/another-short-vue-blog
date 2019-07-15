<template>
  <div class="home">
    <add-blog></add-blog>
  </div>
</template>

<script>
import addBlog from "../components/addBlog";

export default {
  name: "home",
  components: {
    "add-blog": addBlog
  }
};
</script>
