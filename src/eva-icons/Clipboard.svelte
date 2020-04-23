<script>
  export let pattern = "outline";
</script>

{#if pattern === 'outline'}
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
    <g data-name="Layer 2">
      <g data-name="clipboard">
        <rect width="24" height="24" opacity="0" />
        <path
          d="M18 5V4a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2v1a3 3 0 0 0-3 3v11a3 3 0 0 0
          3 3h12a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3zM8 4h8v4H8V4zm11 15a1 1 0 0 1-1
          1H6a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1v1a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V7a1
          1 0 0 1 1 1z" />
      </g>
    </g>
  </svg>
{:else if pattern === 'fill'}
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
    <g data-name="Layer 2">
      <g data-name="clipboard">
        <rect width="24" height="24" opacity="0" />
        <path
          d="M18 4v3a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V4a3 3 0 0 0-3 3v12a3 3 0 0 0
          3 3h12a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3z" />
        <rect x="7" y="2" width="10" height="6" rx="1" ry="1" />
      </g>
    </g>
  </svg>
{/if}
