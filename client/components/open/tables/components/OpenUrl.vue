<template>
  <a
    class="text-gray-700 dark:text-gray-300 hover:underline"
    :href="value"
    target="_blank"
    rel="nofollow"
  >{{ value }}</a>
</template>

<script>
export default {
  components: {},
  props: {
    value: {
      type: String,
      required: true,
    },
  },

  data() {
    return {}
  },

  computed: {},
  mounted() {},

  methods: {},
}
</script>
