@import url("https://fonts.googleapis.com/css?family=Quicksand:400,500,700&subset=latin-ext");
html {
  position: relative;
  overflow-x: hidden !important;
}

body {
  font-family: "Quicksand", sans-serif;
}

a, a:hover {
  text-decoration: none;
}

.icon {
  display: inline-block;
  width: 1em;
  height: 1em;
  stroke-width: 0;
  stroke: currentColor;
  fill: currentColor;
}

.background {
  position: fixed;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
}
.background:after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(45deg, rgba(209, 0, 42, 0.6) 0%, #0E5DC4 100%);
  opacity: 0.9;
}
.background img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  pointer-events: none;
  user-select: none;
}

.item-bg {
  width: 300px;
  height: 500px;
  position: absolute;
  top: 30px;
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 6px 26px 6px rgba(0, 0, 0, 0.25);
  opacity: 0;
  transition: all 0.3s;
  left: -30px;
}
.item-bg.active {
  left: 0;
  top: 0;
  opacity: 1;
}

.news-slider {
  z-index: 2;
  max-width: 1300px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 60px;
}
@media screen and (max-width: 1300px) {
  .news-slider {
    max-width: 1000px;
  }
}
@media screen and (max-width: 576px) {
  .news-slider {
    margin-top: 45px;
  }
}
.news-slider__wrp {
  display: flex;
  align-items: flex-start;
  position: relative;
  z-index: 2;
}
.news-slider__item {
  width: 400px;
  flex-shrink: 0;
}
@media screen and (max-width: 992px) {
  .news-slider__item {
    width: 340px;
  }
}
.news-slider__item.swiper-slide {
  opacity: 0;
  pointer-events: none;
  transition: all 0.3s;
}
.news-slider__item.swiper-slide-active, .news-slider__item.swiper-slide-prev, .news-slider__item.swiper-slide-next {
  opacity: 1;
  pointer-events: auto;
}
.news-slider__ctr {
  position: relative;
  z-index: 12;
}
.news-slider__arrow {
  background: #fff;
  border: none;
  display: inline-flex;
  width: 50px;
  height: 50px;
  justify-content: center;
  align-items: center;
  box-shadow: 0 6px 26px 6px rgba(0, 0, 0, 0.25);
  border-radius: 50%;
  position: absolute;
  top: 50%;
  z-index: 12;
  cursor: pointer;
  outline: none !important;
}
.news-slider__arrow:focus {
  outline: none !important;
}
.news-slider__arrow .icon-font {
  display: inline-flex;
}
.news-slider__arrow.news-slider-prev {
  left: 15px;
  transform: translateY(-50%);
}
.news-slider__arrow.news-slider-next {
  right: 15px;
  transform: translateY(-50%);
}
.news-slider__pagination {
  text-align: center;
  margin-top: 50px;
}
.news-slider__pagination .swiper-pagination-bullet {
  width: 13px;
  height: 10px;
  display: inline-block;
  background: #fff;
  opacity: 0.2;
  margin: 0 5px;
  border-radius: 20px;
  transition: opacity 0.5s, background-color 0.5s, width 0.5s;
  transition-delay: 0.5s, 0.5s, 0s;
}
.news-slider__pagination .swiper-pagination-bullet-active {
  opacity: 1;
  background: #ffffff;
  width: 100px;
  transition-delay: 0s;
}
@media screen and (max-width: 576px) {
  .news-slider__pagination .swiper-pagination-bullet-active {
    width: 70px;
  }
}
.news__item {
  padding: 40px;
  color: #fff;
  border-radius: 10px;
  display: block;
  transition: all 0.3s;
}
@media screen and (min-width: 800px) {
  .news__item:hover {
    color: #222222;
    transition-delay: 0.1s;
  }
  .news__item:hover .news-date, .news__item:hover .news__title, .news__item:hover .news__txt {
    opacity: 1;
    transition-delay: 0.1s;
  }
  .news__item:hover .news__img {
    box-shadow: none;
  }
}
.news__item.active {
  color: #222222;
}
.news__item.active .news-date, .news__item.active .news__title, .news__item.active .news__txt {
  opacity: 1;
}
.news__item.active .news__img {
  box-shadow: none;
}
@media screen and (max-width: 992px) {
  .news__item {
    padding: 30px;
  }
}
@media screen and (max-width: 576px) {
  .news__item {
    padding: 20px;
  }
}
.news-date {
  padding-bottom: 20px;
  margin-bottom: 20px;
  border-bottom: 2px solid;
  display: inline-block;
  opacity: 0.7;
  transition: opacity 0.3s;
}
@media screen and (max-width: 576px) {
  .news-date {
    margin-bottom: 10px;
    display: inline-flex;
    align-items: center;
    padding-bottom: 0;
  }
}
.news-date__title {
  display: block;
  font-size: 32px;
  margin-bottom: 10px;
  font-weight: 500;
}
@media screen and (max-width: 576px) {
  .news-date__title {
    margin-right: 10px;
  }
}
.news-date__txt {
  font-size: 16px;
}
.news__title {
  font-size: 25px;
  font-weight: 500;
  opacity: 0.7;
  margin-top: 10px;
  margin-bottom: 15px;
  transition: opacity 0.3s;
}
@media screen and (max-width: 576px) {
  .news__title {
    font-size: 22px;
    margin-bottom: 10px;
  }
}
.news__txt {
  margin: 10px 0;
  line-height: 1.6em;
  font-size: 15px;
  opacity: 0.7;
  transition: opacity 0.3s;
}
.news__img {
  border-radius: 10px;
  box-shadow: 0 6px 26px 6px rgba(0, 0, 0, 0.25);
  height: 200px;
  margin-top: 30px;
  width: 100%;
  transition: all 0.3s;
  transform-origin: 0% 0%;
}
@media screen and (max-width: 576px) {
  .news__img {
    height: 180px;
    margin-top: 20px;
  }
}
.news__img img {
  max-width: 100%;
  border-radius: 10px;
  height: 100%;
  width: 100%;
}