Run `yarn dev`

Visit `http://localhost:3000/`

Get `Module not found: Can't resolve './fooo.generated.js'`

```
Module not found: Can't resolve './fooo.generated.js'
  4 | import styles from '../styles/Home.module.css'
  5 | 
> 6 | import * as a from "./fooo.generated.js"
  7 | 
  8 | const Home: NextPage = () => {
  9 |   return (
```

_______

Next.js should support this...
