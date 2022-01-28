<template>
  <div class="links">
    <div class="container">
      <div class="links-footer">
        <div class="col">
          <div>
            <h4>dc comics</h4>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Video</a></li>
              <li><a href="#">News</a></li>
            </ul>
          </div>
          <div>
            <h4>Shop</h4>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
        </div>
        <div class="col">
          <div>
            <h4>dc</h4>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Video</a></li>
              <li><a href="#">News</a></li>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
            </ul>
          </div>
        </div>
        <div class="col">
          <div>
            <h4>sites</h4>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
            </ul>
          </div>
        </div>
      </div>

      <div class="logo-footer">
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Links",
};
</script>

<style lang="scss" scoped>

.container {
  display: flex;
  justify-content: space-between;
  height: 300px;
  overflow: hidden;
}

.links {
  background: url("../../assets/img/footer-bg.jpg") no-repeat;
  background-size: cover;
  color: #fff;

  h4 {
    font-size: 20px;
    padding: 10px 10px 10px 0px;
    text-transform: uppercase;
  }

  li {
    list-style: none;
  }

  a {
    color: rgb(189, 180, 180);
    text-decoration: none;
    font-weight: 100;
    font-size: 12px;
  }
}

.links-footer {
  display: flex;
  justify-content: space-around;
}

.col {
  padding: 10px 20px;
}

.logo-footer {
  background: url("../../assets/img/dc-logo-bg.png") no-repeat center;
  background-size: cover;
  width: 450px;
}
</style>
