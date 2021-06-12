<html>
  <p>Hello, world!</p>
  <script>
    const url = new URL(window.location);
    const searchParams = url.searchParams;
    alert("Foo bar baz! " + searchParams.get("foo"));
  </script>
</html>
