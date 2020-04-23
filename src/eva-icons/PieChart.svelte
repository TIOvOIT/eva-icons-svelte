<script>
  export let pattern = "outline";
</script>

{#if pattern === 'outline'}
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
    <g data-name="Layer 2">
      <g data-name="pie-chart">
        <rect width="24" height="24" opacity="0" />
        <path
          d="M13 2a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1 9 9 0 0
          0-9-9zm1 8V4.07A7 7 0 0 1 19.93 10z" />
        <path
          d="M20.82 14.06a1 1 0 0 0-1.28.61A8 8 0 1 1 9.33 4.46a1 1 0 0
          0-.66-1.89 10 10 0 1 0 12.76 12.76 1 1 0 0 0-.61-1.27z" />
      </g>
    </g>
  </svg>
{:else if pattern === 'fill'}
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
    <g data-name="Layer 2">
      <g data-name="pie-chart">
        <rect width="24" height="24" opacity="0" />
        <path
          d="M14.5 10.33h6.67A.83.83 0 0 0 22 9.5 7.5 7.5 0 0 0 14.5 2a.83.83 0
          0 0-.83.83V9.5a.83.83 0 0 0 .83.83z" />
        <path
          d="M21.08 12h-8.15a.91.91 0 0 1-.91-.91V2.92A.92.92 0 0 0 11 2a10 10 0
          1 0 11 11 .92.92 0 0 0-.92-1z" />
      </g>
    </g>
  </svg>
{/if}
