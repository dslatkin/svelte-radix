<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'border top';
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
  <path fill-rule="evenodd" clip-rule="evenodd" d="M14 1.75L1 1.75L1 0.249999L14 0.25L14 1.75Z" />
  <rect x="8" y="10" width={size} height={size} rx=".5" transform="rotate(-180 8 10)" />
  <rect x="2" y="10" width={size} height={size} rx=".5" transform="rotate(-180 2 10)" />
  <rect x="8" y="12" width={size} height={size} rx=".5" transform="rotate(-180 8 12)" />
  <rect x="2" y="12" width={size} height={size} rx=".5" transform="rotate(-180 2 12)" />
  <rect x="8" y="8" width={size} height={size} rx=".5" transform="rotate(-180 8 8)" />
  <rect x="8" y="14" width={size} height={size} rx=".5" transform="rotate(-180 8 14)" />
  <rect x="2" y="8" width={size} height={size} rx=".5" transform="rotate(-180 2 8)" />
  <rect x="2" y="14" width={size} height={size} rx=".5" transform="rotate(-180 2 14)" />
  <rect x="10" y="8" width={size} height={size} rx=".5" transform="rotate(-180 10 8)" />
  <rect x="10" y="14" width={size} height={size} rx=".5" transform="rotate(-180 10 14)" />
  <rect x="12" y="8" width={size} height={size} rx=".5" transform="rotate(-180 12 8)" />
  <rect x="12" y="14" width={size} height={size} rx=".5" transform="rotate(-180 12 14)" />
  <rect x="6" y="8" width={size} height={size} rx=".5" transform="rotate(-180 6 8)" />
  <rect x="6" y="14" width={size} height={size} rx=".5" transform="rotate(-180 6 14)" />
  <rect x="4" y="8" width={size} height={size} rx=".5" transform="rotate(-180 4 8)" />
  <rect x="4" y="14" width={size} height={size} rx=".5" transform="rotate(-180 4 14)" />
  <rect x="8" y="6" width={size} height={size} rx=".5" transform="rotate(-180 8 6)" />
  <rect x="2" y="6" width={size} height={size} rx=".5" transform="rotate(-180 2 6)" />
  <rect x="8" y="4" width={size} height={size} rx=".5" transform="rotate(-180 8 4)" />
  <rect x="2" y="4" width={size} height={size} rx=".5" transform="rotate(-180 2 4)" />
  <rect x="14" y="10" width={size} height={size} rx=".5" transform="rotate(-180 14 10)" />
  <rect x="14" y="12" width={size} height={size} rx=".5" transform="rotate(-180 14 12)" />
  <rect x="14" y="8" width={size} height={size} rx=".5" transform="rotate(-180 14 8)" />
  <rect x="14" y="14" width={size} height={size} rx=".5" transform="rotate(-180 14 14)" />
  <rect x="14" y="6" width={size} height={size} rx=".5" transform="rotate(-180 14 6)" />
  <rect x="14" y="4" width={size} height={size} rx=".5" transform="rotate(-180 14 4)" />
</svg>

<!--
@component
[Go to docs](https://svelte-radix.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'border top';
-->
