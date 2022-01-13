# LIT-REMIXICON

_This is a simple wrapper package to add remixicon icons to lit projects._

https://remixicon.com/

---

### Instructions

```
npm i lit-remixicon
```

Just import it and wrap it in an element.

```ts
import inlineSoSVG from 'lit-remixicon/svg/logos/stack-overflow-fill';
...
...
public render() {
  return html`<i style="display: inline-block; width: 50x; height: 50px;">${inlineSoSVG}</i>`;
}

```

import path is `lit-remixicon/svg/[category]/[icon name]`

You can find the categories and icons at https://remixicon.com/ website.

### dependencies

- Lit
