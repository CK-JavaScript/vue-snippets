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

# Code Snippets

## vue.html

> **`vIf`**

```
v-if="$1"
```

> **`vForI`**

```
v-for="item in $1" :key="item"
```

> **`vForII`**

```
v-for="(item, index) in $1" :key="item"
```

> **`vModel`**

```
v-model="$1"
```

> **`vCData`**

```
:class="{ $1 : $2 }"
```

> **`vCCalc`**

```
:class="[ $1 ? $2 : $3 ]"
```

> **`vStyle`**

```
:style="{}"
```

> **`vSData`**

```
:style="{ $1 : $2 }"
```

> **`vSCalc`**

```
:style="{ $1 : $2 ? $3 : $4}"
```

## vue

> **`vless`**

```vue
<template>
	<div class="$1"></div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped></style>
```

> **`vscss`**

```vue
<template>
	<div class="$1"></div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
```

> **`vvless`**

```vue
<template>
	<div class="$1"></div>
</template>

<script>
export default {
	setup() {},
};
</script>

<style lang="less" scoped></style>
```

> **`vvscss`**

```vue
<template>
	<div class="$1"></div>
</template>

<script>
export default {
	setup() {},
};
</script>

<style lang="scss" scoped></style>
```

> **`vvless-DC`**

```vue
<template>
	<div class="$1"></div>
</template>

<script>
import { defineComponent } from "vue";
export default defineComponent({
	setup() {},
});
</script>

<style lang="less" scoped></style>
```

> **`vvscss-DC`**

```vue
<template>
	<div class="$1"></div>
</template>

<script>
import { defineComponent } from "vue";
export default defineComponent({
	setup() {},
});
</script>

<style lang="scss" scoped></style>
```

> **`vvless-setup`**

```vue
<template>
	<div class="$1"></div>
</template>

<script setup></script>

<style lang="less" scoped></style>
```

> **`vvscss-setup`**

```vue
<template>
	<div class="$1"></div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
```

## Vue Api

> **`iVue`** - 导入 vue

```js
import { $1 } from "vue";
```

> **`vdata`** - v2 data

```js
data() {
  return {
    $1
  }
},
```

> **`vProp`** - v2 props

```js
props: {
  $1: {
    type: $2
  }
},
```

> **`vPD`** - v2 props default

```js
props: {
  $1: {
    type: $2,
    default: $3
  }
},
```

> **`vPDR`** - v2 props default required

```js
props: {
  $1: {
    type: $2,
    default: $3,
    required: true
  }
},
```

> **`vMixins`** - v2 mixins

```js
mixins: [ $1 ],
```

> **`vMethods`** - v2 methods

```js
methods: {
  $1() {

  }
},
```

> **`vComputed`** - v2 computed

```js
computed: {
  $1() {
    return $2
  }
},
```

> **`vCS`** - v2 computed setter

```js
computed: {
  $1: {
    get() {

      return
    },
    set(newValue) {

    }
  }
},
```

> **`vWatch`** - v2 watch

```js
watch: {
  $1(newValue, oldValue) {
    $2
  }
},
```

> **`vWD`** - v2 watch deep

```js
watch: {
  $1: {
    handler(newValue, oldValue) {
      $2
    },
    deep:true,
  }
},
```

> **`vWI`** - v2 watch immediate

```js
watch: {
  $1: {
    handler(newValue, oldValue) {
      $2
    },
    immediate:true,
  }
},
```

> **`vWDI`** - v2 watch deep immediate

```js
watch: {
  $1: {
    handler(newValue, oldValue) {
      $2
    },
    deep:true,
    immediate:true,
  }
},
```

> **`vFilters`** - v2 filters

```js
filters: {
  $1(value) {
    return value;
  }
},
```

> **`vBCreate`** - v2 beforeCreate

```js
beforeCreate () {

},
```

> **`vCreated`** - v2 created

```js
created () {

},
```

> **`vBMount`** - v2 beforeMount

```js
beforeMount () {

},
```

> **`vMounted`** - v2 mounted

```js
mounted () {

},
```

> **`vBUpdate`** - v2 beforeUpdate

```js
beforeUpdate () {

},
```

> **`vUpdated`** - v2 updated

```js
updated () {

},
```

> **`vBUnmount`** - v2 beforeUnmount

```js
beforeUnmount () {

},
```

> **`vUnmounted`** - v2 unmounted

```js
unmounted () {

},
```

> **`vvRef`** - v3 ref

```js
const $1 = ref($2);
```

> **`vvReactive`** - v3 reactive

```js
const $1 = reactive({
	$2
});
```
> **`vvProps`** - v3 defineProps

```js
defineProps({
	$1: {
    type: $2,
    datault: $3,
    required: true
  }
});
```
> **`vvEmits`** - v3 defineEmits

```js
const emit = defineEmits(['$1']);
```
> **`vvEmits`** - v3 useSlots

```js
const slots = useSlots()
```
> **`vvEmits`** - v3 useAttrs

```js
const attrs = useAttrs()
```
> **`vvEmits`** - v3 defineExpose

```js
defineExpose({
  $1
})
```
> **`vvComputed`** - v3 computed

```js
const $1 = reactive({
	$2
});
```
> **`vvWatch`** - v3 watch

```js
watch(() => $1, (newValue, oldValue) => {
  
})
```
> **`vvWI`** - v3 watch immediate

```js
watch(() => $1, (newValue, oldValue) => {
  
},{ immediate: true })
```
> **`vvWA`** - v3 watch arr

```js
watch([$1, $2], ([new$1, new$2], [old$1, old$2]) => {
  
})
```
> **`vvWAI`** - v3 watch arr immediate

```js
watch([$1, $2], ([new$1, new$2], [old$1, old$2]) => {
  
},{ immediate: true })
```
> **`vvWE`** - v3 watchEffect

```js
watchEffect(() => {
  
})
```
> **`vvBMounted`** - v3 onBeforeMount

```js
onBeforeMount(($1) => {

})
```
> **`vvMounted`** - v3 onMounted

```js
onMounted(($1) => {

})
```
> **`vvBUpdate`** - v3 onBeforeUpdate

```js
onBeforeUpdate(($1) => {

})
```
> **`vvUpdated`** - v3 onUpdated

```js
onUpdated(($1) => {

})
```
> **`vvBUnmount`** - v3 onBeforeUnmount

```js
onBeforeUnmount(($1) => {

})
```
> **`vvUnmounted`** - v3 onUnmounted

```js
onUnmounted(($1) => {

})
```
## vuex
> **`vStore`** - vuex store

```js
import Vue from "vue";
import Vuex from "vuex";
Vue.use(Vuex);
export default new Vuex.Store({
  state: {},
  mutations: {},
  actions: {},
});
```
> **`vGetters`** - vuex getters

```js
getters: {
  $1(state) {
    return state.$1;
  }
}
```
> **`vMutations`** - vuex mutations

```js
mutations: {
  $1(state, $2) {
    $3;
  }
}
```
> **`vActions`** - vuex actions

```js
actions: {
  $1({commit}, $2) {
    commit($1,$2);
  }
}
```
> **`vModule`** - vuex module

```js
export default {
  namespaced: true,
  state: {},
  mutations: {},
  actions: {},
};
```

## vue-router
> **`vRouter`** - vueRouter router

```js
import Vue from "vue";
import VueRouter from "vue-router";

Vue.use(VueRouter);

const routes = [
  {
    path: "",
    name: "",
    alias: "",
    component: ,
  },
];

const router = new VueRouter({
  mode: "history",
  base: process.env.BASE_URL,
  routes,
});

export default router;
```

## JavaScript

> **`cls`** - log 字符:变量

```js
console.log('$1 >>',$1);
```
> **`clv`** - log 变量

```js
console.log($1);
```
> **`jF`** - 箭头函数

```js
($1) => {
  $2
};
```
> **`jFN`** - 带名字的箭头函数

```js
const $1 = () => {
  $2
};
```
> **`AFE`** - array.forEach(()=>{})

```js
$1.forEach(item => {
  $2
})
```
> **`forLoop`** - for 循环

```js
for (let i = 0; i < $1; i++) {
 $2
}
```
> **`fin`** - forIn 循环

```js
for (const item in $1) {
  $2
}
```
> **`fof`** - forOf 循环

```js
for (const item of $1) {
  $2
}
```

## less & scss
> **`fcc`** - flex 横向垂直居中

```css
display: flex;
align-items: center;
justify-content: center;
```
# Contact
有什么建议和意见请加微信联系：
> Wechat ID：C-ChenKun

# Version：1.0.3

