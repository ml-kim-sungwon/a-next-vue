<template>
  <div class="category">
    <div class="category-title">
      <img
        src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/367_21.png?v=1585806724"
        width="100%"
      />
    </div>
    <ul class="category-banner">
      <li>
        <img
          src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/101.png?v=1585803537"
          width="176"
        />
      </li>
      <li>
        <img
          src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/101.png?v=1585803537"
          width="176"
        />
      </li>
      <li>
        <img
          src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/101.png?v=1585803537"
          width="176"
        />
      </li>
      <li>
        <img
          src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/101.png?v=1585803537"
          width="176"
        />
      </li>
      <li>
        <img
          src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/101.png?v=1585803537"
          width="176"
        />
      </li>
      <li>
        <img
          src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/101.png?v=1585803537"
          width="176"
        />
      </li>
      <li>
        <img
          src="https://cdn.shopify.com/s/files/1/0071/0855/8911/files/101.png?v=1585803537"
          width="176"
        />
      </li>
    </ul>
    <ul class="category-list">
      <li v-for="(item, index) in items">
        <div class="category_item">
          <div class="category_item-img">
            <img :src="item.image" width="212" />
          </div>
          <div class="category_item-title">{{item.title}}</div>
          <div class="category_item-price">¥{{item.price}}</div>
        </div>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2300"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        },
        {
          image:
            "//cdn.shopify.com/s/files/1/0071/0855/8911/products/n2723s-630932_150x.jpg?v=1588222701",
          title: "ギンガムミニトップス N2751S",
          price: "2400"
        }
      ]
    };
  }
};
</script>
<style lang="scss" scoped>
.category {
  width: 1170px;
  .category-title {
    text-align: center;
  }
  .category-banner {
    display: flex;
    margin-top: 26px;
    background: #f4f0f7;
    overflow: hidden;
    > li {
      list-style-type: none;
    }
  }
  .category-list {
    margin-top: 24px;
    width: 1170px;
    > li {
      float: left;
      width: 212px;
      list-style-type: none;
      margin-left: 20px;
    }
  }
}

.category_item {
  text-align: center;
  .category_item-img {
  }
  .category_item-title {
    margin-top: 20px;
  }
  .category_item-price {
    margin-top: 8px;
  }
}
</style>