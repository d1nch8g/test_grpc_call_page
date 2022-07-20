<script lang="ts">
</script>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <h2>Request metadata</h2>
    <p>Some text..</p>
    <!-- add request related metadata over here -->
  </div>
  <div class="column middle" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
  <div class="column right" style="background-color:#ccc;">
    <h2>Column 3</h2>
    <p>Some text..</p>
  </div>
</div>

<style>
  * {
    box-sizing: border-box;
  }

  /* Create three unequal columns that floats next to each other */
  .column {
    float: left;
    padding: 10px;
    height: 800px; /* Should be removed. Only for demonstration */
  }

  .left {
    width: 20%;
  }
  .right {
    width: 40%;
  }
  .middle {
    width: 40%;
  }

  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
</style>
