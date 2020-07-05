# vue-vanta

> Animated website backgrounds in a few lines of code.

### How to use?
```bash
npm install vue-vanta
```

### Example

```vue
<template>
  <v-vanta effect="waves" :options=options></v-vanta>
</template>

<script>
  import VVanta from 'veu-vanta';
  export default {
    components: { VVanta },
    data () {
      return {
        options: {
            mouseControls: true,
            touchControls: true,
            minHeight: 500.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00
        }
      }
    }
  }
</script>
```

### Options
|    Property    |    Description   |   type   |	default	|
| -----------------  | ---------------- | :--------: | :----------: |
| effect         | | String | birds |
| options  | Each effect has its own specific parameters. Explore them all at www.vantajs.com! | Object | |
