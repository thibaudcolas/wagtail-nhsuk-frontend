
# Promo

```py
from wagtail.core.models import Page
from wagtail.core.fields import StreamField

from wagtailnhsukfrontend.blocks import PromoBlock,

class MyPage(Page):
  body = StreamField([
      ...
      ('promo', PromoBlock()),
      ...
  ])
```

# Promo Group

A Promo Group is a collection of promos in a 2-column or 3-column grid layout.

```py
from wagtail.core.models import Page
from wagtail.core.fields import StreamField

from wagtailnhsukfrontend.blocks import PromoGroupBlock,

class MyPage(Page):
  body = StreamField([
      ...
      ('promo_group', PromoGroupBlock()),
      ...
  ])
```

## Reference

[Frontend Library](https://github.com/nhsuk/nhsuk-frontend/tree/master/packages/components/promo)
