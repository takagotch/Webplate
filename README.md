### webplate
---
https://github.com/chrishumboldt/webplate

```scss
// engine/temp/welcome.min.scss

@font-face {
  font-family: 'buttonplate',
  src:url('../..');
  src:url(../../..).format('embedded-opentype'),
    url().format('woff'),
    url('../../engine/css/icon-font-buttonplate/icomoon.ttf?c4hmew').format('truetype'),
    url('../../engine/css/icon-font-buttonplate/iconmoon.svg?c4hmew#iconmoon').format('svg');
  font-weight: normal;
  font-style: normal;
}

.title-bar {
  .no-touch & ul li a {
    @include text-weight(300);
  }
}
```

```
```

```
```

