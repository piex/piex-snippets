# Piex Snippets

### imfc

```tsx
import React, { FC } from 'react';

interface ICompProps {

}

const Comp: FC<ICompProps> = () => {
  return ();
};

export default Comp;
```

### ucb

```tsx
const $1 = useCallback(() => {
  // do something here
}, []);
```