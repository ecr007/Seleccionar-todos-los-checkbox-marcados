# Seleccionar todos los checkbox-marcados

```javascript
$('.class-btn-call').click(function(){
    var ids = $(".ecr-class-array-checkboxes:checkbox:checked").map(function(){
		    return $(this).data('id');
		}).get();
});
```
