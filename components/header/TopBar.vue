<template>
  <div class="col top-bar">
    <div class="top-bar-nav">
      <a href="#" class="top-bar-nav__item">
        <div class="account">sdgs</div>
        <div>
          <User />
        </div>
      </a>
      <a href="#" class="top-bar-nav__item">
        <Search />
      </a>
    </div>
  </div>
</template>

<style src="~/assets/header/top-bar.scss" lang="scss"></style>
<script>
import User from "~/components/icons/User";
import Search from "~/components/icons/Search";
export default {
  components: {Search, User}
}
</script>
