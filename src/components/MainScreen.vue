<template>
  <section>
    <!--    Container-->
    <div class="container">
      <!--      Swiper-->
      <swiper
          :modules="modules"
          :slides-per-view="1"
          :space-between="50"
          navigation
          :pagination="{ clickable: true }"
          :scrollbar="{ draggable: true }"
          @swiper="onSwiper"
          @slideChange="onSlideChange"
      >
        <!--        BorutoScreen-->
        <swiper-slide class="boruto_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 70 [ENG]</h3>
              <h3>Boruto: Naruto Next Generations</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/img/boruto.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        BorutoScreen-->
        <!--        OnePieceScreen-->
        <swiper-slide class="onepiece_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--          MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--          MainScreenTitle-->
            <!--          MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 1064 [ENG]</h3>
              <h3>One Piece</h3>
            </div>
            <!--          MainScreenInfo-->
            <!--          MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--          MainScreenDesc-->
            <!--          MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--          MainScreenActions-->
            <!--          MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--          MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--          MainScreenBtn-->
              <!--          MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--          MainScreenBtn-->
            </div>
            <!--          MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/img/one_pie.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        OnePieceScreen-->
        <!--        TokyoScreen-->
        <swiper-slide class="tokyo_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 127 [ENG]</h3>
              <h3>Tokyo Revengers</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/img/tokyo_ravengers.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        TokyoScreen-->
        <!--        OnePunchManScreen-->
        <swiper-slide class="onepucnch_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 182 [ENG]</h3>
              <h3>One Punch Man</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/img/one_punchmen.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        SpyScreen-->
        <swiper-slide class="spy_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 4 [ENG]</h3>
              <h3>Spy x Family</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/img/spyxfamily.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
      </swiper>
      <!--      Swiper-->
    </div>
    <!--    Container-->
  </section>
</template>

<script>
import {Navigation, Pagination, Scrollbar, A11y} from 'swiper';

import {Swiper, SwiperSlide} from 'swiper/vue'


import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
import 'swiper/css/scrollbar';


export default {
  name: "MainScreen",
  components: {
    Swiper,
    SwiperSlide
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper)
    };
    const onSlideChange = () => {
      console.log('slide change')
    };
    return {
      onSwiper,
      onSlideChange,
      modules: [Navigation, Pagination, Scrollbar, A11y],
    };
  }
}
</script>

<style scoped>
@import "../assets/css/style.css";
@import "../assets/css/main_screen.css";
</style>