# Repositorie to save different dom functions

### Function to resize

```javascript
const mediaQueryEvent = window.matchMedia('(min-width: 768px)');

mediaQueryEvent.addEventListener('change', (event) => {
    if(event.matches){
        console.log('if previous value is lower');
    }else{
        console.log('if previous value is higher');
    }
});
```
