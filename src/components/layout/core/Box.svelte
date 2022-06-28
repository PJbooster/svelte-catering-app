<script>
  export let w = "auto";
  export let h = "auto";
  export let m = "0";
  export let p = "0";
  export let bg = "none";
</script>

<div
  style:width={w}
  style:height={h}
  style="display: block; padding: {p}; margin: {m}; background-color: {bg}"
>
  <slot />
</div>
