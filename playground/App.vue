<script>
import TestMultiplySrcImport from './src-import/TestMultiplySrcImport.vue'
import TestBlockSrcImport from './src-import/TestBlockSrcImport.vue'
import TestScopedCss from './css/TestScopedCss.vue'
import TestCssModules from './css/TestCssModules.vue'
import TestCustomBlock from './custom/TestCustomBlock.vue'
import TestHmr from './hmr/TestHmr.vue'

export default {
  name: 'App',
  components: {
    TestMultiplySrcImport,
    TestScopedCss,
    TestBlockSrcImport,
    TestCssModules,
    TestCustomBlock,
    TestHmr,
  },
}
</script>

<template>
  <div>
    <h1>Vite-Plugin-Vue2 Playground</h1>
    111
    <br>
    <router-view />
    <br>
    111
    <TestMultiplySrcImport />
    <TestBlockSrcImport />
    <TestScopedCss />
    <TestCssModules />
    <TestCustomBlock />
    <TestHmr />
  </div>
</template>
