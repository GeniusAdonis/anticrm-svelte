<script lang="ts">
  export let size: 'small' | 'medium' | 'large'
  const fill: string = 'currentColor'
</script>

<svg class="svg-{size}" {fill} xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
  <path
    d="M11.5,1H6.6C5.3,1,4.2,2,4.1,3.3C2.9,3.5,2,4.6,2,5.8v6.7C2,13.9,3.1,15,4.5,15h4.9c1.3,0,2.4-1,2.5-2.3 c1.2-0.2,2.1-1.2,2.1-2.5V3.5C14,2.1,12.9,1,11.5,1z M9.4,14H4.5C3.7,14,3,13.3,3,12.5V5.8c0-0.7,0.5-1.3,1.1-1.4v5.8 c0,1.4,1.1,2.5,2.5,2.5h4.3C10.8,13.4,10.2,14,9.4,14z M13,10.2c0,0.8-0.7,1.5-1.5,1.5H6.6c-0.8,0-1.5-0.7-1.5-1.5V3.5 C5.1,2.7,5.8,2,6.6,2h4.9C12.3,2,13,2.7,13,3.5V10.2z"
  />
</svg>
