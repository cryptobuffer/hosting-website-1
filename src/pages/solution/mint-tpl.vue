<template>
  <div class="mint-tpl pos-r">
    <div class="ta-c pos-center w90p" style="max-width: 550px">
      <h2>Mint Template</h2>
      <div class="fz-15 mt-8 ta-l">
        <p>
          The current project template is for you to create NFTs, enter the
          contract address to set environment variables and deploy the project.
          Come and try it out!
        </p>
      </div>
      <div class="mt-15">
        <v-btn
          color="#A27EC6"
          :to="`/new/clone-flow?s=${encodeURIComponent(
            'https://github.com/Mint-Box/mint-box-template'
          )}&e=contractAddr:0x86Bc6E0608C1F2E3507E868526F2653cD411d88C`"
        >
          <span class="white-0">Deploy</span>
        </v-btn>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.mint-tpl {
  background: #f4e4e6 url(/img/bg/mint-tpl.jpg) center center no-repeat;
  background-size: cover;
  min-height: 70vh;
}
</style>