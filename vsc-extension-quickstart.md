# Piex Snippets

## snippets

### imfc

```tsx
import { FC } from 'react';

const Comp: FC = () => {
  return ();
};

export default Comp;
```

### imfcp

```tsx
import { FC } from 'react';

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

### ur

```tsx
const [toggle, setToggle] = useReducer((state) => !state, false);
```
