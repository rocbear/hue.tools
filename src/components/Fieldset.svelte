<script lang="ts">
  export let label: string
  export let className: string = ''
</script>

<div class="border rounded-xl border-gray-700 p-6 pt-7 relative {className}">
  <h5
    class="absolute left-3 top-0 transform -translate-y-1/2 bg-gray-900 px-3 text-lg font-bold"
  >
    {label}
  </h5>

  <slot />
</div>
