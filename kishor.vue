const app = Vue.createApp({
    data() {
      return {
        text: ''
      }
    },
    methods: {
      writeText() {
        this.text = 'Hello Wrold!'
      }
    }
  })