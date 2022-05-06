<script>
  let toggled = false;
  const handleClick = () => (toggled = !toggled);
</script>

<p on:click={handleClick}>
  State is {toggled ? "ON" : "OFF"}
</p>
