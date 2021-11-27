<template>
  <div>
    <Heading title="Redirecting..." />
  </div>
</template>

<script>
export default {
  head: {
    title: 'Invite',
  },
  mounted() {
    window.location.href =
      'https://discord.com/oauth2/authorize?client_id=867303025394974731&permissions=397283815127&scope=bot%20applications.commands'
  },
}
</script>
