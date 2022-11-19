<template>
  <!--  Header-->
  <header>
    <!--  TopHeader-->
    <div class="top_header">
      <!--    Container-->
      <div class="container">
        <!--      TopHead-->
        <div class="top_head df">
          <!--        TopHeadItems-->
          <div class="top_head_items df">
            <!--          TopHeadItem-->
            <div class="top_head_item df ">
              <img src="../../assets/img/icons/glasses.svg" alt="" class="cursor">
              <p class="cursor">Read Now</p>
            </div>
            <!--          TopHeadItem-->
            <!--          TopHeadItem-->
            <div class="top_head_item df">
              <img src="../../assets/img/icons/play.svg" alt="" class="cursor">
              <p class="cursor">Anime Online</p>
            </div>
            <!--          TopHeadItem-->
          </div>
          <!--        TopHeadItems-->
          <!--        FollowItems-->
          <div class="follow_items">
            <!--          FollowItemWrap-->
            <div class="follow_item_wrap df">
              <!--            FollowItemTitle-->
              <div class="follow_item_title">
                <p>Follow Us:</p>
              </div>
              <!--            FollowItemTitle-->
              <!--            FollowItem-->
              <div class="follow_item df cursor">
                <img src="../../assets/img/icons/dashicons_reddit.svg" alt="">
                <p>Reddit</p>
              </div>
              <!--            FollowItem-->
              <!--            FollowItem-->
              <div class="follow_item df cursor">
                <img src="../../assets/img/icons/akar-icons_twitter-fill.svg" alt="">
                <p>Twitter</p>
              </div>
              <!--            FollowItem-->
              <!--            FollowItem-->
              <div class="follow_item df cursor">
                <img src="../../assets/img/icons/discord.svg" alt="">
                <p>Discord</p>
              </div>
              <!--            FollowItem-->
            </div>
            <!--          FollowItemWrap-->
          </div>
          <!--        FollowItems-->
        </div>
        <!--      TopHead-->
      </div>
      <!--    Container-->

    </div>
    <!--  TopHeader-->

    <!--  BottomHeader-->
    <div class="bottom_header">
      <!--    Container-->
      <div class="container">
        <!--        BottomHead-->
        <div class="bottom_head">
          <!--          BottomHeadItems-->
          <div class="bottom_head_items df">
            <!--          BottomHeadItem-->
            <div class="bottom_head_item df">
              <!--              Logo-->
              <div class="logo">
                <a href="#">
                  <img class="logo_img" src="../../assets/img/logo.png" alt="">
                </a>
              </div>
              <!--              Logo-->
              <!--              Filter-->
              <div class="filter df">
                <div class="filter_text cursor">
                  <p>FILTER</p>
                </div>
                <input type="text" placeholder="Search manga...">
                <img src="../../assets/img/icons/ant-design_search-outlined.svg" alt="">
              </div>
              <!--              Filter-->

            </div>
            <!--          BottomHeadItem-->
            <!--          BottomHeadItem-->
            <div class="bottom_head_item">
              <!--              Menu-->
              <div class="menu">
                <!--                MenuUl-->
                <ul class="menu_ul df">
                  <li><a href="#">Completed</a></li>
                  <li><a href="#">Types</a></li>
                  <li><a href="#">A-Z List</a></li>
                  <li><a href="#">News</a></li>
                </ul>
                <!--                MenuUl-->

              </div>
              <!--              Menu-->
            </div>
            <!--          BottomHeadItem-->
            <!--          BottomHeadItem-->
            <div class="bottom_head_item">
              <!--              Modes-->
              <div class="modes df">
                <!--                HeadItem-->
                <div class="head_item df cursor">
                  <img src="../../assets/img/icons/moon.svg" alt="">
                  <p>Dark Mode</p>
                </div>
                <!--                HeadItem-->
                <!--                HeadItem-->
                <div class="head_item df cursor">
                  <img src="../../assets/img/icons/account.svg" alt="">
                  <p>Member</p>
                </div>
                <!--                HeadItem-->
              </div>
              <!--              Modes-->
            </div>
            <!--          BottomHeadItem-->
          </div>
          <!--          BottomHeadItems-->
        </div>
        <!--        BottomHead-->

      </div>
      <!--    Container-->
    </div>
    <!--  BottomHeader-->
  </header>
  <!--  Header-->
</template>

<script>
export default {
  name: 'v-Header',
}
</script>

<style scoped>
@import "../../assets/css/header.css";
@import "../../assets/css/style.css";
</style>
