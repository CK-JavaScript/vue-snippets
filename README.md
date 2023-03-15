# VSCode Snippets

VSCode 代码片段包含，直接安装插件即可使用。

```text
- vue.html
- vue
- vueRouter
- vuex
- JavaScript
```

# Prefix

## JavaScript

| Prefix       | Snippets                               |
| ------------ | -------------------------------------- |
| `cls`        | console.log( string )                  |
| `clv`        | console.log( variable )                |
| `fun`        | function name(){}                      |
| `of`         | name(){}                               |
| `af`         | arrow function                         |
| `afn`        | named arrow function                   |
| `for`        | for loop                               |
| `fof`        | fof loop                               |
| `fin`        | fin loop                               |
| `sc`         | switch case loop                       |
| `sit`        | setInterval                            |
| `st`         | setTimeout                             |
| `promise`    | new Promise                            |
| `promiseTCF` | new Promise().then().catch().finally() |

## import

| Prefix | Snippets                |
| ------ | ----------------------- |
| `imp`  | import $2 from '$1'     |
| `imd`  | import { $2 } from '$1' |

## Vue.html

| Prefix  | Snippets                                |
| ------- | --------------------------------------- |
| `click` | @click="$1"                             |
| `if`    | v-if="$1"                               |
| `eif`   | v-else-if="$1"                          |
| `else`  | v-else="$1"                             |
| `fori`  | v-for="item in $1" :key="item"          |
| `forii` | v-for="(item, index) in $1" :key="item" |
| `model` | v-model="$1"                            |
| `cData` | :class="{ $1 : $2 }"                    |
| `cCalc` | :class="[ $1 ? $2 : $3 ]"               |
| `style` | :style="{}"                             |
| `sData` | :style="{ $1 : $2 }"                    |
| `sCalc` | :style="{ $1 : $2 ? $3 : $4}"           |

## Vue base

| Prefix         | Snippets                               |
| -------------- | -------------------------------------- |
| `vcss`         | vue2 css 基础代码                      |
| `vless`        | vue2 less 基础代码                     |
| `vscss`        | vue2 scss 基础代码                     |
| `vvcss`        | vue3 css 基础代码                      |
| `vvless`       | vue3 less 基础代码                     |
| `vvscss`       | vue3 scss 基础代码                     |
| `vvcss-DC`     | vue3 css 基础代码 ( defineComponent )  |
| `vvless-DC`    | vue3 less 基础代码 ( defineComponent ) |
| `vvscss-DC`    | vue3 scss 基础代码 ( defineComponent ) |
| `vvcss-setup`  | vue3 css 基础代码 ( setup 语法糖 )     |
| `vvless-setup` | vue3 less 基础代码 ( setup 语法糖 )    |
| `vvscss-setup` | vue3 scss 基础代码 ( setup 语法糖 )    |

## Vue2

| Prefix        | Snippets                             |
| ------------- | ------------------------------------ |
| `vdata`       | vue2 data                            |
| `vComponents` | vue2 components                      |
| `vProps`      | vue2 props                           |
| `vPropsD`     | vue2 props ( default )               |
| `vPropsDR`    | vue2 props ( default required )      |
| `vEmit`       | vue2 emit                            |
| `vMixins`     | vue2 混入 mixins                     |
| `vMethods`    | vue2 方法 methods                    |
| `vComputed`   | vue2 计算属性 computed               |
| `vComputedS`  | vue2 计算属性 computed ( setter )    |
| `vWatch`      | vue2 侦听器 watch                    |
| `vWatchD`     | vue2 侦听器 watch ( deep )           |
| `vWatchI`     | vue2 侦听器 watch ( immediate )      |
| `vWatchDI`    | vue2 侦听器 watch ( deep immediate ) |
| `vFilters`    | vue2 过滤器 filters                  |
| `vNextNick`   | vue2 NextNick                        |
| `vBCreate`    | vue2 生命周期 beforeCreate           |
| `vCreated`    | vue2 生命周期 created                |
| `vBMount`     | vue2 生命周期 beforeMount            |
| `vMounted`    | vue2 生命周期 mounted                |
| `vBUpdate`    | vue2 生命周期 beforeUpdate           |
| `vUpdated`    | vue2 生命周期 updated                |
| `vBUnmount`   | vue2 生命周期 beforeUnmount          |
| `vUnmounted`  | vue2 生命周期 unmounted              |

## Vue3

| Prefix          | Snippets                                  |
| --------------- | ----------------------------------------- |
| `vvFun`         | vue3 定义一个函数                         |
| `vvSetup`       | vue3 setup(){}                            |
| `vvSetup-param` | vue3 setup(props, {attrs, slots, emit}){} |
| `vvRoute`       | vue3 useRoute                             |
| `vvRouter`      | vue3 useRouter                            |
| `vvStore`       | vue3 useStore                             |
| `vvRef`         | vue3 ref                                  |
| `vvToRef`       | vue3 toRef                                |
| `vvIsRef`       | vue3 isRef                                |
| `vvReactive`    | vue3 reactive                             |
| `vvToRefs`      | vue3 toRefs                               |
| `vvUnref`       | vue3 unref                                |
| `vvIsProxy`     | vue3 isProxy                              |
| `vvIsReactive`  | vue3 isReactive                           |
| `vvReadonly`    | vue3 readonly                             |
| `vvIsReadonly`  | vue3 isReadonly                           |
| `vvProps`       | vue3 defineProps                          |
| `vvEmits`       | vue3 defineEmits                          |
| `vvSlots`       | vue3 useSlots                             |
| `vvAttrs`       | vue3 useAttrs                             |
| `vvExpose`      | vue3 暴露数据 defineExpose                |
| `vvComputed`    | vue3 计算属性 computed                    |
| `vvWatch`       | vue3 侦听器 watch                         |
| `vvWatchD`      | vue3 侦听器 watch ( deep )                |
| `vvWatchI`      | vue3 侦听器 watch ( immediate )           |
| `vvWatchDI`     | vue3 侦听器 watch ( deep immediate )      |
| `vvWatchArr`    | vue3 侦听器 Watch 多个 ref                |
| `vvWatchObj`    | vue3 侦听器 Watch reactive 中单个 key     |
| `vvWE`          | vue3 侦听器 watchEffect                   |
| `vvBMounted`    | vue3 生命周期 onBeforeMount               |
| `vvMounted`     | vue3 生命周期 onMounted                   |
| `vvBUpdate`     | vue3 生命周期 onBeforeUpdate              |
| `vvUpdated`     | vue3 生命周期 onUpdated                   |
| `vvBUnmount`    | vue3 生命周期 onBeforeUnmount             |
| `vvUnmounted`   | vue3 生命周期 onUnmounted                 |
| `vvGP`          | vue3 全局属性 globalProperties            |
| `vvNextTick`    | vue3 NextTick                             |

## Vue2&Vue3

| Prefix   | Snippets                   |
| -------- | -------------------------- |
| `dProp`  | vue2 default prop          |
| `rProp`  | vue2 required prop         |
| `rdProp` | vue2 required default prop |

## vueRouter

| Prefix       | Snippets                                  |
| ------------ | ----------------------------------------- |
| `vrPush`     | v2 this.$router.push()                    |
| `vrReplace`  | v2 this.$router.replace()                 |
| `vrGo`       | v2 this.$router.go()                      |
| `vvrPush`    | v3 router.push()                          |
| `vvrReplace` | v3 router.replace()                       |
| `vvrGo`      | v3 router.go()                            |
| `vrBEach`    | beforeEach 全局前置守卫                   |
| `vrBResolve` | beforeResolve 全局解析守卫                |
| `vrAEach`    | afterEach 全局后置钩子                    |
| `vrBEnter`   | beforeEnter 路由独享的守卫                |
| `vrBREnter`  | beforeRouteEnter 组件内的守卫 ( Enter )   |
| `vrBRUpdate` | beforeRouteUpdate 组件内的守卫 ( Update ) |
| `vrBRLeave`  | beforeRouteLeave 组件内的守卫 ( Leave )   |

## vuex

| Prefix       | Snippets                |
| ------------ | ----------------------- |
| `vCommit`    | vue2 提交一个 commit    |
| `vDispatch`  | vue2 提交一个 dispatch  |
| `vvCommit`   | vue3 store.commit("")   |
| `vvDispatch` | vue3 store.dispatch("") |

## pinia

| Prefix    | Snippets          |
| --------- | ----------------- |
| `pinia`   | pinia base        |
| `pToRefs` | pinia storeToRefs |
| `pPatch`  | pinia $patch      |

# Contact

有什么建议和意见请加微信联系：

> Wechat ID：C-ChenKun
