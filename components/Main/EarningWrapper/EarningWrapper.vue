<template>
  <div class="earning-wrapper text-center">
    <div class="single-earning">
      <div
        class="earning-title"
        data-aos="fade-up"
        data-aos-duration="750"
        data-aos-ease="ease-in"
      >
        <img
          src="../../../assets/images/icons/erning-01.png"
          class="ml-5"
          alt
        />
        <h2>
          Bitcoin (
          <span>BTC</span>)
        </h2>
      </div>
      <div class="single-item">
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10 </span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-down-icon
                  size="1x"
                  color="red"
                  class="custom-class"
                ></arrow-down-icon>
              </i>
            </span>
          </li>
        </ul>
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-up-icon
                  size="1x"
                  class="custom-class"
                  color="green"
                ></arrow-up-icon>
              </i>
            </span>
          </li>
        </ul>
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-up-icon
                  size="1x"
                  class="custom-class"
                  color="green"
                ></arrow-up-icon>
              </i>
            </span>
          </li>
        </ul>
      </div>
    </div>
    <div class="single-earning">
      <div
        class="earning-title"
        data-aos="fade-up"
        data-aos-duration="750"
        data-aos-ease="ease-in"
      >
        <img
          src="../../../assets/images/icons/erning-02.png"
          class="ml-5"
          alt
        />
        <h2>
          Ethereum (
          <span>ETM</span>)
        </h2>
      </div>
      <div class="single-item">
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-down-icon
                  size="1x"
                  color="red"
                  class="custom-class"
                ></arrow-down-icon>
              </i>
            </span>
          </li>
        </ul>
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-down-icon
                  size="1x"
                  color="red"
                  class="custom-class"
                ></arrow-down-icon>
              </i>
            </span>
          </li>
        </ul>
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-up-icon
                  size="1x"
                  color="green"
                  class="custom-class"
                ></arrow-up-icon>
              </i>
            </span>
          </li>
        </ul>
      </div>
    </div>
    <div class="single-earning">
      <div
        class="earning-title"
        data-aos="fade-up"
        data-aos-duration="750"
        data-aos-ease="ease-in"
      >
        <img
          src="../../../assets/images/icons/erning-03.png"
          class="ml-5"
          alt
        />
        <h2>
          LiteCoin (
          <span>LTC</span>)
        </h2>
      </div>
      <div class="single-item">
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD </span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-down-icon
                  size="1x"
                  color="red"
                  class="custom-class"
                ></arrow-down-icon>
              </i>
            </span>
          </li>
        </ul>
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-up-icon
                  size="1x"
                  color="green"
                  class="custom-class"
                ></arrow-up-icon>
              </i>
            </span>
          </li>
        </ul>
        <ul data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
          <li>
            <span>USD</span>
            <span>17,427,10</span>
          </li>
          <li>
            <span>%2h</span>
            <span>
              <i
                >3.44
                <arrow-down-icon
                  size="1x"
                  color="red"
                  class="custom-class"
                ></arrow-down-icon>
              </i>
            </span>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import { ArrowUpIcon } from "vue-feather-icons";
import { ArrowDownIcon } from "vue-feather-icons";

export default {
  components: {
    ArrowUpIcon,
    ArrowDownIcon
  }
};
</script>

<style>
.earning-wrapper {
  background: #ffffff;
  box-shadow: 0 0 80px 0px rgba(0, 0, 0, 0.15);
  border-radius: 5px;
  padding: 50px;
  display: flex;
  justify-content: space-between;
  transform: scale(1.05);
}
.earning-wrapper .single-earning {
  width: 27%;
}
.earning-wrapper .single-earning .earning-title {
  display: flex;
  margin-bottom: 40px;
  margin-right: 15px;
}
.earning-wrapper .single-earning .earning-title img {
  height: 39px;
  width: auto;
}
.earning-wrapper .single-earning .earning-title h2 {
  color: #562ad8;
  font-size: 24px;
  font-weight: 600;
  line-height: 39px;
  margin-left: 20px;
}
.single-earning .single-item {
  display: flex;
  justify-content: space-between;
}
.single-item ul li {
  margin-bottom: 30px;
}
.single-item ul li:last-child {
  margin-bottom: 0;
}
.single-earning .single-item ul li span {
  display: block;
}
.custom-class {
  display: inherit;
}
</style>
