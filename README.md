# vuetotastkk1

## A mobile toast plugin for vue

## Useage

```javascript
npm install vuetotastkk1

import vuetotastkk1 from 'vuetotastkk1'

Vue.use(vuetotastkk1)

this.$toast.show("hello, toast")

this.$toast.show("hello, toast", {
    duration: 3000
}) 

this.$toast.show("hello, toast", funcion() {

})
```