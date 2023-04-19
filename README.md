DownCount
=========

jQuery countdown plugin that accounts for timezone.

#Usage

```JS
$('.countdown').downCount({
    date: '08/27/2013 12:00:00',
    offset: -5
    locale: de
}, function () {
    alert('WOOT WOOT, done!');
});
```

#Options
Option | Description
---|---
date | Target date, ex `08/27/2013 12:00:00`
offset | UTC Timezone offset
locale | Language to use, defaults to 'en'

You can also append a callback function which is called when countdown finishes.
