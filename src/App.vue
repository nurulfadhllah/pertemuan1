<template>
  <DeclarativeRendering />
  <AttributeBinding />
  <EventListeners />
  <FormBindings />
  <ConditionalRendering />
</template>

<script>
import DeclarativeRendering from "./components/DeclarativeRendering.vue";
import AttributeBinding from "./components/AttributeBinding.vue";
import EventListeners from "./components/EventListeners.vue";
import FormBindings from "./components/FormBindings.vue";
import ConditionalRendering from "./components/ConditionalRendering.vue";



export default {
  components: {
    DeclarativeRendering,
    AttributeBinding,
    EventListeners,
    FormBindings,
    ConditionalRendering,

  },
};
</script>