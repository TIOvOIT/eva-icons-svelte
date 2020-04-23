<script>
  export let pattern = "outline";
</script>

{#if pattern === 'outline'}
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
    <g data-name="Layer 2">
      <g data-name="toggle-left">
        <rect
          width="24"
          height="24"
          transform="rotate(180 12 12)"
          opacity="0" />
        <path
          d="M15 5H9a7 7 0 0 0 0 14h6a7 7 0 0 0 0-14zm0 12H9A5 5 0 0 1 9 7h6a5 5
          0 0 1 0 10z" />
        <path
          d="M9 9a3 3 0 1 0 3 3 3 3 0 0 0-3-3zm0 4a1 1 0 1 1 1-1 1 1 0 0 1-1 1z" />
      </g>
    </g>
  </svg>
{:else if pattern === 'fill'}
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
    <g data-name="Layer 2">
      <g data-name="toggle-left">
        <rect
          x=".02"
          y=".02"
          width="23.97"
          height="23.97"
          transform="rotate(179.92 12.002 11.998)"
          opacity="0" />
        <path
          d="M15 5H9a7 7 0 0 0 0 14h6a7 7 0 0 0 0-14zM9 15a3 3 0 1 1 3-3 3 3 0 0
          1-3 3z" />
        <path d="M9 11a1 1 0 1 0 0 2 1 1 0 0 0 0-2z" />
      </g>
    </g>
  </svg>
{/if}
