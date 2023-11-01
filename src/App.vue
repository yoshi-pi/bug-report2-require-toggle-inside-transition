<template>
  <Transition>
    <FooComp />
  </Transition>
  <Transition>
    <div v-if="true">A</div>
    <div>B</div>
  </Transition>
</template>
