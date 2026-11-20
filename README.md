<button id="btn">Change Page Color</button>

<script>
const arr1 = ['yellow', 'red', 'salmon'];    

while (true) {
  const item = arr1[Math.floor(Math.random() * arr1.length)];
  document.getElementById('btn').addEventListener('click', () => {
    document.body.style.backgroundColor = item;
  });

}

</script>