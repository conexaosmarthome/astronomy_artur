<!-- ADD THIS INSIDE <head> -->
<link rel="manifest" href="manifest.json">

<!-- ADD BEFORE </body> -->
<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('./sw.js');
}
</script>
