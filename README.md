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

### um

```tsx
const $1 = useMemo(() => ${2:/* return a value */}, []);
```

### us

```tsx
const [state, setState] = useState(0);
```
