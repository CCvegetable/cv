<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hi~ 我是涵伃</template>
    歡迎來到我的個人網站


  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>專業技能</template>

    Revit、Dynamo、Navisworks、Twinmotion、AutoCAD、Ms Project、QGIS、C++、Python、Vue.js

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>學歷</template>

    大學 | 國立台北科技大學 ( 2020 – 2024/06 )
    <br>
    高中 | 國立中科實驗高中 ( 2016 – 2019/06 )



  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>作品連結</template>
    
    <a href="https://youtu.be/isqqhhC9oGc">土木館 BIM渲染動畫</a>
    <br>
    <a href="https://youtu.be/O323wbdeWpU">土木館 剖面展示</a>
    <br>
    <a href="https://youtu.be/uaKimvEjWuk">土木館 Navisworks漫遊</a>
    <br>
    <a href="https://youtu.be/cytELHRe6xA">土木館 4D TimeLiner展示</a>
    <br>
    <a href="https://youtu.be/khbeNL45T8Y">土木館 穿越</a>
  
  
  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>聯絡資料</template>

    Email : cecitsai30218@gmail.com.tw
    <br>
    連絡電話 : 0905-361-691

    
  </WelcomeItem>
</template>
