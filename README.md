# booksync
Create your own Booksync widget using v3 of their API

```javascript
<script type="text/javascript">
$$(function() {
  var options = {
    date_format  : 'M dd, yy',
    rental_codes : [123456]
  }
  $('.booksync-single').booksync_widget(options);
});
</script>
```
```javascript
<script type="text/javascript">
var options = {
  date_format        : 'M dd, yy',
  rental_codes       : [75928,75929,78463,75930,75933,78461]
}

$('.booksync-many').booksync_widget(options);
</script>
```
