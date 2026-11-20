<button id="btn">Change Page Color</button>

<script>
const arr1 = ["yellow", "red", "salmon"];

document.getElementById('btn').addEventListener('click', () => {
  const item = arr1[Math.floor(Math.random() * arr1.length)];
  document.body.style.backgroundColor = item;
});
</script>