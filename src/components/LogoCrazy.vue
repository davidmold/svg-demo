<template>
  <svg viewBox="0 0 46 80">
    <g>
      <rect class="cls-1" x="8.58" y="6" width="38" height="38" transform-origin="27 27">
        <animate attributeName="rx" values="0;20;0" dur="2s" repeatCount="indefinite" />
        <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0  0" dur="1.5s" repeatCount="indefinite" />
        <animate attributeName="fill" values="#fff;#0ff;#f0f;#fff" dur="2s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite" />
      </rect>
      <rect class="cls-1" x="8.58" y="29.58" width="38" height="38" transform="translate(-26.27 33.73) rotate(-45)">
        <animate attributeName="fill" values="#f00;#0f0;#00f;#f00" dur="4s" repeatCount="indefinite" />
      </rect>
    </g>
  </svg>
</template>

<script>
export default {

}
</script>

<style>
   .cls-1{
    fill:#f00;
    stroke:#231f20;
    stroke-miterlimit:10;
  }
</style>
