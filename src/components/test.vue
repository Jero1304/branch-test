<template>
    <div>
      <h1>{{ title }}</h1>
      <p>{{ description }}</p>
    </div>
</template>
  
<script>
    export default {
        data() {
            return {
            title: 'Eccoci nel Main!',
            description: 'Lorem ipsum super figo che possa descrivere un main super figo e super funzionale, enjoy the main!'
            };
        }
    };
</script>
  
  <style scoped>
  h1 {
    color: green;
  }

  p {
    color: rgb(44, 198, 44);
  }

  </style>