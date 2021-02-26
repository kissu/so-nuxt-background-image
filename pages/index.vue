<template>
  <div>
    <img src="~static/img/info/production/pic4.jpg" class="t22" />
    <a href="/page/fresco-art" class="btn t23">First text</a>

    <div class="hr t24"></div>
    <h2 class="t25">Second text</h2>

    <ul class="services">
      <li
        :style="{
          backgroundImage: `url(${require('@/static/img/info/production/pic5.jpg')})`,
        }"
        class="sq"
      >
        <div class="n">Third text</div>
      </li>
    </ul>
  </div>
</template>
