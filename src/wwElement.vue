<template>
  <button>
    <wwLayout path="slot" />
  </button>
</template>

<script>
export default {
  props: {
    content: { type: Object, required: true },
    uid: { type: String, required: true },
    wwFrontState: { type: Object, required: true },
    wwEditorState: { type: Object, required: true },
  },
};
</script>
