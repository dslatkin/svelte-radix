<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'border bottom';
</script>

<svg
  width={size}
  height={size}
  {...$$restProps}
  {role}
  aria-label={ariaLabel}
  on:*
  viewBox="0 0 15 15"
  fill={color}
  xmlns="http://www.w3.org/2000/svg"
>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M1 13.25L14 13.25V14.75L1 14.75V13.25Z" />
  <rect x="7" y="5" width={size} height={size} rx=".5" />
  <rect x="13" y="5" width={size} height={size} rx=".5" />
  <rect x="7" y="3" width={size} height={size} rx=".5" />
  <rect x="13" y="3" width={size} height={size} rx=".5" />
  <rect x="7" y="7" width={size} height={size} rx=".5" />
  <rect x="7" y="1" width={size} height={size} rx=".5" />
  <rect x="13" y="7" width={size} height={size} rx=".5" />
  <rect x="13" y="1" width={size} height={size} rx=".5" />
  <rect x="5" y="7" width={size} height={size} rx=".5" />
  <rect x="5" y="1" width={size} height={size} rx=".5" />
  <rect x="3" y="7" width={size} height={size} rx=".5" />
  <rect x="3" y="1" width={size} height={size} rx=".5" />
  <rect x="9" y="7" width={size} height={size} rx=".5" />
  <rect x="9" y="1" width={size} height={size} rx=".5" />
  <rect x="11" y="7" width={size} height={size} rx=".5" />
  <rect x="11" y="1" width={size} height={size} rx=".5" />
  <rect x="7" y="9" width={size} height={size} rx=".5" />
  <rect x="13" y="9" width={size} height={size} rx=".5" />
  <rect x="7" y="11" width={size} height={size} rx=".5" />
  <rect x="13" y="11" width={size} height={size} rx=".5" />
  <rect x="1" y="5" width={size} height={size} rx=".5" />
  <rect x="1" y="3" width={size} height={size} rx=".5" />
  <rect x="1" y="7" width={size} height={size} rx=".5" />
  <rect x="1" y="1" width={size} height={size} rx=".5" />
  <rect x="1" y="9" width={size} height={size} rx=".5" />
  <rect x="1" y="11" width={size} height={size} rx=".5" />
</svg>

<!--
@component
[Go to docs](https://svelte-radix.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'border bottom';
-->
