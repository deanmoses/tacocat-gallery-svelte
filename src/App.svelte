<script lang="ts">
  import Page from "./Page.svelte";
  import Header from "./Header.svelte";
  import Footer from "./Footer.svelte";
  import Nav from "./Nav.svelte";
  import PageContent from "./PageContent.svelte";
  import Sidebar from "./Sidebar.svelte";
  import MainContent from "./MainContent.svelte";
</script>

<Page>
  <Header>
    <span slot="title">Dean, Lucie, Felix and Milo Moses</span>
    <span slot="short-title">The Moses Family</span>
  </Header>
  <Nav />
  <PageContent>
    <Sidebar>Sidebar</Sidebar>
    <MainContent>Content</MainContent>
  </PageContent>
  <Footer />
</Page>
