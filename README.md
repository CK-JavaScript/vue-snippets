# VSCode Snippets

VSCode 代码片段包含，直接安装插件即可使用。

```text
- vue.html
- vue
- JavaScript
- typescript
- less
- scss
```

# Prefix

## JavaScript

| Prefix      | Snippets                               |
| ----------- | -------------------------------------- |
| `cls`       | console.log( ' $1 >> ', $1 );          |
| `clv`       | console.log( $1 )                      |
| `fun`       | function name(){}                      |
| `OF`        | name(){}                               |
| `AF`        | arrow function                         |
| `AFN`       | named arrow function                   |
| `for`       | for loop                               |
| `fof`       | fof loop                               |
| `fin`       | fin loop                               |
| `SC`        | switch case loop                       |
| `SIT`       | setInterval                            |
| `ST`        | setTimeout                             |
| `newPro`    | new Promise                            |
| `newProTCF` | new Promise().then().catch().finally() |

## import

| Prefix | Snippets                |
| ------ | ----------------------- |
| `imp`  | import $2 from '$1'     |
| `imd`  | import { $2 } from '$1' |

## Vue.html

| Prefix   | Snippets                                |
| -------- | --------------------------------------- |
| ` if`    | v-if="$1"                               |
| ` eif`   | v-else-if="$1"                          |
| ` else`  | v-else="$1"                             |
| ` fi`    | v-for="item in $1" :key="item"          |
| ` fii`   | v-for="(item, index) in $1" :key="item" |
| ` model` | v-model="$1"                            |
| ` cData` | :class="{ $1 : $2 }"                    |
| ` cCalc` | :class="[ $1 ? $2 : $3 ]"               |
| ` style` | :style="{}"                             |
| ` sData` | :style="{ $1 : $2 }"                    |
| ` sCalc` | :style="{ $1 : $2 ? $3 : $4}"           |

## Vue base

| Prefix          | Snippets                               |
| --------------- | -------------------------------------- |
| `vcss `         | vue2 css 基础代码                      |
| `vless `        | vue2 less 基础代码                     |
| `vscss`         | vue2 scss 基础代码                     |
| `vvcss`         | vue3 css 基础代码                      |
| `vvless`        | vue3 less 基础代码                     |
| `vvscss`        | vue3 scss 基础代码                     |
| `vvcss-DC`      | vue3 css 基础代码 ( defineComponent )  |
| `vvless-DC`     | vue3 less 基础代码 ( defineComponent ) |
| `vvscss-DC`     | vue3 scss 基础代码 ( defineComponent ) |
| `vvcss-setup`   | vue2 css 基础代码 ( setup 语法糖 )     |
| `vvless-setup ` | vue2 less 基础代码 ( setup 语法糖 )    |
| `vvscss-setup ` | vue2 scss 基础代码 ( setup 语法糖 )    |

## Vue2

| Prefix        | Snippets                             |
| ------------- | ------------------------------------ |
| `vdata`       | vue2 data                            |
| `vComponents` | vue2 components                      |
| `vProp`       | vue2 props                           |
| `vPD`         | vue2 props ( default )               |
| `vPDR`        | vue2 props ( default required )      |
| `vEmit`       | vue2 emit                            |
| `vMixins`     | vue2 混入 mixins                     |
| `vMethods`    | vue2 方法 methods                    |
| `vComputed`   | vue2 计算属性 computed               |
| `vCS`         | vue2 计算属性 computed ( setter )    |
| `vWatch`      | vue2 侦听器 watch                    |
| `vWD`         | vue2 侦听器 watch ( deep )           |
| `vWI`         | vue2 侦听器 watch ( immediate )      |
| `vWDI`        | vue2 侦听器 watch ( deep immediate ) |
| `vFilters`    | vue2 过滤器 filters                  |
| `vBCreate`    | vue2 生命周期 beforeCreate           |
| `vCreated`    | vue2 生命周期 created                |
| `vBMount`     | vue2 生命周期 beforeMount            |
| `vMounted`    | vue2 生命周期 mounted                |
| `vBUpdate`    | vue2 生命周期 beforeUpdate           |
| `vUpdated`    | vue2 生命周期 updated                |
| `vBUnmount`   | vue2 生命周期 beforeUnmount          |
| `vUnmounted`  | vue2 生命周期 unmounted              |
| `vCommit`     | vue2 提交一个 commit                 |
| `vDispatch`   | vue2 提交一个 dispatch               |

## Vue3

| Prefix         | Snippets                                  |
| -------------- | ----------------------------------------- |
| `vvFun`        | vue3 定义一个函数                         |
| `vvSetup`      | vue3 setup(){}                            |
| `vvRoute`      | vue3 useRoute                             |
| `vvRouter`     | vue3 useRouter                            |
| `vvStore`      | vue3 useStore                             |
| `vvCommit`     | vue3 store.commit("")                     |
| `vvDispatch`   | vue3 store.dispatch("")                   |
| `vvRef`        | vue3 ref                                  |
| `vvReactive`   | vue3 reactive                             |
| `vvProps`      | vue3 defineProps                          |
| `vvEmits`      | vue3 defineEmits                          |
| `vvSlots`      | vue3 useSlots                             |
| `vvAttrs`      | vue3 useAttrs                             |
| `vvExpose`     | vue3 暴露数据 defineExpose                |
| `vvComputed`   | vue3 计算属性 computed                    |
| `vvWatch`      | vue3 侦听器 watch                         |
| `vvWD`         | vue3 侦听器 watch ( deep )                |
| `vvWI`         | vue3 侦听器 watch ( immediate )           |
| `vvWDI`        | vue3 侦听器 watch ( deep immediate )      |
| `vvWMRef`      | vue3 侦听器 Watch more ref                |
| `vvWSReactive` | vue3 侦听器 Watch single data in reactive |
| `vvWE`         | vue3 侦听器 watchEffect                   |
| `vvBMounted`   | vue3 生命周期 onBeforeMount               |
| `vvMounted`    | vue3 生命周期 onMounted                   |
| `vvBUpdate`    | vue3 生命周期 onBeforeUpdate              |
| `vvUpdated`    | vue3 生命周期 onUpdated                   |
| `vvBUnmount`   | vue3 生命周期 onBeforeUnmount             |
| `vvUnmounted`  | vue3 生命周期 onUnmounted                 |
| `vvGP`         | vue3 全局属性 globalProperties            |
| `vvNextTick`   | vue3 NextTick                             |

## vueRouter

| Prefix       | Snippets                                  |
| ------------ | ----------------------------------------- |
| `vrBEach`    | beforeEach 全局前置守卫                   |
| `vrBResolve` | beforeResolve 全局解析守卫                |
| `vrAEach`    | afterEach 全局后置钩子                    |
| `vrBEnter`   | beforeEnter 路由独享的守卫                |
| `vrBREnter`  | beforeRouteEnter 组件内的守卫 ( Enter )   |
| `vrBRUpdate` | beforeRouteUpdate 组件内的守卫 ( Update ) |
| `vrBRLeave`  | beforeRouteLeave 组件内的守卫 ( Leave )   |

## less & scss

| Prefix                 | Snippets            |
| ---------------------- | ------------------- |
| `flex`                 | display flex        |
| `fcc`                  | flex 横向垂直居中   |
| `txt1` ,`txt2`, `txt3` | 文本溢出省略 1~3 行 |
| `scrollX`              | X 滚动条样式        |
| `scrollY`              | Y 滚动条样式        |

## pinia

| Prefix         | Snippets          |
| -------------- | ----------------- |
| `pinia`        | pinia base        |
| `pinia-toRefs` | pinia storeToRefs |

# Contact

有什么建议和意见请加微信联系：

> Wechat ID：C-ChenKun
