<script setup>
import Header from "@/components/Header.vue"
import Slider from "@/components/Slider.vue"
import Image from "@/components/Image.vue"
import ImageText from "@/components/ImageText.vue"
import Card from "@/components/Card.vue"
import Banner from "@/components/Banner.vue"
import Text from "@/components/Text.vue"
import Footer from "@/components/Footer.vue"
</script>

<template>
  <Header element="nexon" />
  <main>
    <Slider element="nexon" title="슬라이드 유형" />
    <Image element="nexon section" title="포트폴리오가 실력이다." />
    <ImageText element="nexon section gray" title="이미지 텍스트 유형" />
    <Card element="section nexon" title="웹스토리보이 강의" />
    <Banner element="nexon" title="배너 영역" />
    <Text element="section nexon" title="텍스트 유형01" />
  </main>
  <Footer element="nexon section gray" />
</template>
