<script lang="ts">
  import Drawer, { AppContent, Content } from "@smui/drawer";
  import DataTable, { Head, Body, Row, Cell } from "@smui/data-table";
</script>

<div class="drawer-container">
  <Drawer>
    <DataTable table$aria-label="People list" style="max-width: 100%;">
      <Head>
        <Row>
          <Cell>gRPC Clicker</Cell>
        </Row>
      </Head>
      <Body>
        <Row>
          <Cell>Steve</Cell>
        </Row>
        <Row>
          <Cell>Sharon</Cell>
        </Row>
        <Row>
          <Cell>Rodney</Cell>
        </Row>
        <Row>
          <Cell>Mack</Cell>
        </Row>
        <Row>
          <Cell>Mack</Cell>
        </Row>
        <Row>
          <Cell>Mack</Cell>
        </Row>
        <Row>
          <Cell>Mack</Cell>
        </Row>
      </Body>
    </DataTable>
  </Drawer>

  <AppContent class="app-content">
    <main class="main-content">
      App content.
      <br />
      <pre class="status">Clicked: nani</pre>
    </main>
  </AppContent>
</div>

<style>
  /* These classes are only needed because the
    drawer is in a container on the page. */
  .drawer-container {
    position: relative;
    display: flex;
    border: 1px solid
      var(--mdc-theme-text-hint-on-background, rgba(0, 0, 0, 0.1));
    overflow: hidden;
    z-index: 0;
  }

  * :global(.app-content) {
    flex: auto;
    overflow: auto;
    position: relative;
    flex-grow: 1;
  }

  .main-content {
    overflow: auto;
    padding: 16px;
    height: 100%;
    box-sizing: border-box;
  }
</style>
