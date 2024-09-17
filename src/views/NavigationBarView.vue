<script lang="ts">
import { RouterLink } from 'vue-router'

export default defineComponent({
  components: {
    RouterLink
  }
})
</script>

<template>
  <nav class="flex justify-between lg:p-4 bg-gray-100">
    <div>
      <RouterLink class="text-3xl font-extrabold text-gray-600" to="/">MotorPH</RouterLink>
    </div>
    <div class="flex items-center justify-center gap-4">
      <!-- Introduction including: {Purpuse,Scope,Defitions,Acronyms,Abbreviations, References, Overview} -->
      <!-- <RouterLink to="/introduction">Introduction</RouterLink> -->
      <!-- Overall Description: Product perspective, Product function, user classes and characteristics, operating environment, Design and Implementation Constrains, Assumptions and Dependencies -->
      <RouterLink class="hover:underline duration-150" to="/overall-description"
        >Overall Description</RouterLink
      >
      <!-- Specific Requirements: Functional Requirements,Non-Functional Requirements ,External Interface Requirements,System Features,Use Cases,Data Requirements-->
      <RouterLink class="hover:underline duration-150" to="/specific-requirements"
        >Specific Requirements</RouterLink
      >
      <!-- System Architecture: Overview, Component Diagrams, Data Flow Diagrams, Design Considerations -->
      <RouterLink class="hover:underline duration-150" to="/system-architecture"
        >System Architecture</RouterLink
      >
      <!-- Appendices: Glossary, List of figures and tables, change history -->
      <RouterLink class="hover:underline duration-150" to="/appendices">Appendices</RouterLink>
      <RouterLink class="hover:underline duration-150" to="/contributor">Contributor</RouterLink>
    </div>
  </nav>
</template>
