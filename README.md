
<!---
anusha-chebolu/anusha-chebolu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<h1 id="greeting">Hi there</h1>

<script>
  var greetings = ["Hi there", "I'm Anusha"];
  var currentGreeting = 0;
  setInterval(function() {
    currentGreeting = (currentGreeting + 1) % greetings.length;
    document.getElementById("greeting").textContent = greetings[currentGreeting];
  }, 3000); // Change text every 3000 milliseconds (3 seconds)
</script>


