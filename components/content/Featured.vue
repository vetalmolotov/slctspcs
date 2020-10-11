<template>
  <div class="featured-products row">
    <div class="featured-products__item col-sm-4">
      <!--
          Очевидно, что сам блок с продуктом нужно сделать отдельным компонентом
          и туда передавать необходимые пропсы, а не копировать, как сделано ниже.
          В реакте это делается через .map() и что-то типа такого:
          <Product
            type={props.productType}
            image={props.productImage}
            ...
          />
          как это делается на Vue я пока не знаю
          -->
      <a href="#" class="featured-product">
        <div class="featured-product__type">FULL RIMMED</div>
        <div class="featured-product__image">
          <img src="/images/reglaze-fr.jpg">
        </div>
        <div class="featured-product__price">₴937.71</div>
        <div class="featured-product__additional">Including Lenses & Coatings</div>
        <div class="featured-product__button">Start Reglaze Now »</div>
      </a>
    </div>
    <div class="featured-products__item col-sm-4">
      <a href="#" class="featured-product">
        <div class="featured-product__type">SEMI RIMLESS</div>
        <div class="featured-product__image">
          <img src="images/reglaze-sr.jpg">
        </div>
        <div class="featured-product__price">₴1250.28</div>
        <div class="featured-product__additional">Including Lenses & Coatings</div>
        <div class="featured-product__button">Start Reglaze Now »</div>
      </a>
    </div>
    <div class="featured-products__item col-sm-4">
      <a href="#" class="featured-product">
        <div class="featured-product__type">RIMLESS</div>
        <div class="featured-product__image">
          <img src="images/reglaze-rimless.jpg">
        </div>
        <div class="featured-product__price">₴1562.85</div>
        <div class="featured-product__additional">Including Lenses & Coatings</div>
        <div class="featured-product__button">Start Reglaze Now »</div>
      </a>
    </div>
  </div>
</template>

<style src="~/assets/content/featured-products.scss" lang="scss"></style>
