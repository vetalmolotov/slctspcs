<template>
  <div class="row">
    <section class="product-specifications specifications">
      <!-- tabs -->
      <input type="radio" name="tabs" id="tab1" class="information" checked>
      <label for="tab1" class="specifications-tab">Information</label>

      <input type="radio" name="tabs" id="tab2" class="reviews">
      <label for="tab2" class="specifications-tab">Reviews (50)</label>

      <!-- tabs content-->
      <div class="specifications-content information">
        <p class="specifications-content__title">
          Nunc egestas posuere enim, eu maximus erat posuere eget
        </p>
        <p class="specifications-content__text">
          Sed ut mi mollis, consequat nulla lacinia, hendrerit turpis. Nulla sapien magna, interdum quis pretium nec, pharetra at felis. Curabitur dictum sapien est, eget ultricies turpis porta vel. Nam suscipit nec lacus sed imperdiet. Vestibulum a purus risus. Nulla et dictum augue, nec efficitur mi. Nam sit amet pretium elit. Aliquam congue, ligula id vehicula vestibulum, orci ex vulputate lacus, ac malesuada elit dolor eget ex. Sed quis aliquet risus, ut cursus lectus. In eget lorem tellus.
        </p>
      </div>
      <div class="specifications-content reviews">
        <p class="specifications-content__title">
          Maximus erat posuere eget
        </p>
        <p class="specifications-content__text">
          Quisque eleifend varius nisi nec sagittis. Nulla ullamcorper imperdiet justo, ut venenatis purus lobortis ut. Nunc sagittis urna et hendrerit sodales. Nunc molestie risus nec fringilla lacinia. Nulla facilisi. Etiam neque velit, tristique eget sollicitudin eget, placerat at metus. Proin dictum lobortis velit, id suscipit orci faucibus ut. Aliquam erat volutpat. Vivamus feugiat justo in diam placerat, id dignissim elit auctor. Vestibulum scelerisque sem et lobortis ultricies. Morbi suscipit nulla urna. Suspendisse potenti. Nullam varius quam sed nisl dignissim, vel faucibus ipsum blandit. Vivamus at suscipit augue. Nam finibus gravida lorem eu viverra. Praesent rhoncus imperdiet ultricies. Nullam pretium cursus augue auctor vulputate. Quisque a convallis diam commodo eget diam id, eleifend dictum libero. Etiam varius, nisi vel dignissim sodales, enim dui posuere mauris, in aliquet lorem eros eget neque.
        </p>
      </div>
    </section>
  </div>
</template>
<style src="~/assets/content/tabs-custom.scss" lang="scss"></style>
