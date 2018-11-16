# booksync
Create your own Booksync widget using v3 of their API

```javascript
<script type="text/javascript">
$$(function() {
  var options = {
    date_format  : 'M dd, yy',
    rental_codes : [123456,765432]
  }
  $('.mini-be-booksync-single').booksync_widget(options);
});
</script>
```
