# Project2
<div class="d3"></div>
<p>Credit: <a href="https://observablehq.com/d/b1017c81b8425c54">Data collection that describes the # of times I remove/put on my glasses/contacts. by Gabrielle Velasco</a></p>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/d/b1017c81b8425c54.js?v=3";
(new Runtime).module(define, name => {
  if (name === "d3") return Inspector.into(".d3")();
});
</script>
