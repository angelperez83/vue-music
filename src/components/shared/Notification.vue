<template lang="pug">
  .container
    .columns
      .column.is-5.is-offset-4
        .notification.is-danger
          slot(name="body") Error
</template>

<style lang="scss" scoped>
  .notification {
      margin: 10px
  }
</style>