# vuetotastkk

## A mobile toast plugin for vue

## Useage

```javascript
import vuetotastkk from 'vuetotastkk'

Vue.use(vuetotastkk)

this.$toast.show("hello, toast")

this.$toast.show("hello, toast", {
    duration: 3000
}) 

this.$toast.show("hello, toast", funcion() {

})
```