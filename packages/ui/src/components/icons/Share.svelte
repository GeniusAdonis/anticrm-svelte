<script lang="ts">
  export let size: 'small' | 'medium' | 'large'
  const fill: string = 'currentColor'
</script>

<svg class="svg-{size}" {fill} viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
  <path
    d="M13.3,7.5c-0.3,0-0.5,0.2-0.5,0.5v5c0,0.4-0.4,0.7-0.8,0.7H4c-0.5,0-0.8-0.3-0.8-0.7V8c0-0.3-0.2-0.5-0.5-0.5S2.2,7.7,2.2,8 v5c0,1,0.8,1.7,1.8,1.7h8c1,0,1.8-0.8,1.8-1.7V8C13.8,7.7,13.6,7.5,13.3,7.5z"
  />
  <path
    d="M6.2,5.1l1.5-1.5v6.3c0,0.3,0.2,0.5,0.5,0.5s0.5-0.2,0.5-0.5V3.6l1.5,1.5c0.1,0.1,0.2,0.1,0.4,0.1c0.1,0,0.3,0,0.4-0.1 c0.2-0.2,0.2-0.5,0-0.7L8.5,2c0,0-0.1-0.1-0.2-0.1c-0.1,0-0.1,0-0.2,0c0,0,0,0,0,0c0,0,0,0,0,0c-0.1,0-0.1,0-0.2,0C8,2,7.9,2,7.9,2 c0,0,0,0-0.1,0L5.5,4.3c-0.2,0.2-0.2,0.5,0,0.7C5.7,5.2,6,5.2,6.2,5.1z"
  />
</svg>
