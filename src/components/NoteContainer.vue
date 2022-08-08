<script>
import NoteSelectors from "./NoteSelectors.vue";
import NoteEditor from "./NoteEditor.vue";

export default {
  components: {
    NoteSelectors,
    NoteEditor,
  },
};
</script>

<template>
  <NoteSelectors />
  <NoteEditor />
  <div class="note-container"></div>
</template>
