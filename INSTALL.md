### [Mantine](https://mantine.dev/)

#### Install using npm

```bash
npm i dracula-mantine -S
```

#### Activating theme

```jsx
import { MantineProvider } from '@mantine/core'
import { DraculaTheme } from 'mantine-dracula'
function Demo() {
  return (
    // Pass DraculaTheme to theme prop of MantineProvider
    <MantineProvider theme={DraculaTheme}>
      <App />
    </MantineProvider>
  )
}
```
