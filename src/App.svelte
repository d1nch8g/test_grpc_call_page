<script lang="ts">
  let protoName = "petstore";
  let protoVersion = "v1";
  let protoAdress = "localhost:8080";
  let serviceName = "PetSerivce";
  let protoCallName = "GetPets";
</script>

<div class="row">
  <div class="column left">
    <h2>Metadata</h2>

    <table>
      <tr>
        <td>Proto </td>
        <td>{protoName} </td>
      </tr>
      <tr>
        <td>Version </td>
        <td>{protoVersion} </td>
      </tr>
      <tr>
        <td>Adress </td>
        <td>{protoAdress} </td>
      </tr>
      <tr>
        <td>Service </td>
        <td>{serviceName} </td>
      </tr>
      <tr>
        <td>Call </td>
        <td>{protoCallName} </td>
      </tr>
      <tr>
        <td>Call </td>
        <td>{protoCallName} </td>
      </tr>
    </table>
  </div>

  <div class="column middle">
    <h2>Request</h2>
    <p>Some text..</p>
  </div>

  <div class="column right">
    <h2>Response</h2>
    <p>Some text..</p>
  </div>
</div>

<style>
  table {
    text-align: left;
    position: relative;
    border-collapse: collapse;
    width: 100%;
  }
  td {
    border: 1px solid #999;
    padding: 20px;
  }

  * {
    box-sizing: border-box;
  }

  .column {
    float: left;
    padding: 10px;
    height: 800px; /* Should be removed. Only for demonstration */
  }

  .left {
    width: 20%;
    border-right: 1px solid #6e6e6e;
  }
  .right {
    width: 40%;
  }
  .middle {
    width: 40%;
    border-right: 1px solid #6e6e6e;
  }

  .row:after {
    content: "";
    display: table;
    clear: both;
  }
</style>
