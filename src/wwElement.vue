<script>
export default {
  props: {
    content: { type: Object, required: true },
    wwFrontState: { type: Object, required: true },
    wwEditorState: { type: Object, required: true },
    randomProp: { type: String, required: false },
  },
};
</script>

<template>
  <div>
    <span> {{ randomProp }}</span>
    <wwLayout path="slot" />
  </div>
</template>
