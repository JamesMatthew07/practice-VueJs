<!-- <script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style> -->

<!-- <template>
  <div>
    <input v-model="priceOfProduct" type="number" />
    <p>Tax: {{ taxPercentage }}</p>
    <p>Total: {{ finalTotal }}</p>
  </div>
</template>

<script setup lang="ts">
import { computed, ref } from 'vue'

const priceOfProduct = ref(0)
const taxPercentage = 0.5

const finalTotal = computed(() => {
  return priceOfProduct.value + priceOfProduct.value * taxPercentage
})

// const addPrice = () => {
//   priceOfProduct++
// }
</script> -->

<!-- <template>
  <div :class="changeColor" class="box"></div>
  <button @click="change">Click Me!</button>
</template>

<script setup lang="ts">
import { ref, computed } from 'vue'

const changeAll = ref(true)

const changeColor = computed(() => {
  return changeAll.value ? 'green' : 'gray'
})

const change = () => {
  changeAll.value = !changeAll.value
}
</script>

<style>
.box {
  height: 100px;
  width: 100px;
  border: 2pc solid red;
}

.green {
  background-color: green;
}

.gray {
  background-color: gray;
}
</style> -->

<!-- <template>
  <a :href="link">Click Me</a>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const link = ref('https://digiplus.sg.larksuite.com/docx/Qnt6dvbpoo86AZxhC3Gl5jFtgBd')
</script> -->

<!-- <template>
  <div>
    <input v-model="price" type="number" />
    <p>Tax: {{ taxComputation }}</p>
    <p>Total: {{ totalSpent }}</p>
  </div>
</template>

<script setup lang="ts">
import { ref, computed, watch } from 'vue'

const price = ref(0)
const taxComputation = 0.5

const totalSpent = computed(() => {
  return price.value + price.value * taxComputation
})

watch(totalSpent, (oldValue, newValue) => {
  console.log(`The total was changed from ${newValue} t0 ${oldValue}`)
})
</script> -->

<!-- <template>
  <div>This is a list of numbers</div>
  <ul>
    <li v-for="number in count" :key="number.id">
      {{ number.number }}
    </li>
  </ul>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const count = ref([
  { id: 1, number: 1 },
  { id: 2, number: 2 },
  { id: 3, number: 3 },
])
</script> -->
