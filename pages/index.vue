<template>

  <div class="container-fluid app">
    <header class="container-fluid app-container app-header">
      <section class="row">
        <Delivery />
        <Logo />
        <TopBar />
      </section>
    </header>
    <section class="container-fluid app-container app-content">
        <BasicInfo />
    </section>
    <section class="container-fluid app-container app-featured">
        <Featured />
    </section>
    <section class="container-fluid app-container app-tabs-custom">
      <TabsCustom />
    </section>
    <section class="container-fluid app-container app-tabs-bootstrap">
      <TabsBootstrap />
    </section>
  </div>
</template>

<script>
import Delivery from "~/components/header/Delivery";
import Logo from "~/components/header/Logo";
import TopBar from "~/components/header/TopBar";
import BasicInfo from "~/components/content/BasicInfo";
import Featured from "~/components/content/Featured";
import TabsCustom from "~/components/content/TabsCustom";
import TabsBootstrap from "~/components/content/TabsBootstrap";
export default {
  components: {TabsBootstrap, TabsCustom, Featured, BasicInfo, TopBar, Delivery, Logo},
}
</script>

<style>

</style>
