<template>
    <article>
        <header class="tabs">
            <ul>
                <li v-for="(tab, index) in tabs" :key="index"></li>
                <div class=" nav" :class="{'is-active' : tab.active}">
                    {{ tab.name }}
                </div>
            </ul>
        </header>
        <section class="tab-details">
            <slot></slot>
        </section>
    </article>
</template>

<script>
import {defineComponent, reactive, provide, onMounted, onBeforeMount, toRefs, VNode} from "vue";
interface TabProps {
  title: string;
}

export default defineComponent({
  name: "Tabs",
  setup(_, {slots}) {
    const state = reactive({
      selectedIndex: 0,
      tabs: [] as VNode<TabProps>[],
      count: 0
    });

    provide("TabsProvider", state);

    const selectTab = (i: number) => {
      state.selectedIndex = i;
    };

    onBeforeMount(() => {
      if (slots.default) {
        state.tabs = slots.default().filter((child) => child.type.name === "Tab");
      }
    });

    onMounted(() => {
      selectTab(0);
    });

    return {...toRefs(state), selectTab};
  }
});
</script>

<style scoped>

</style>