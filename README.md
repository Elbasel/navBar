# NavBar

# Simple navbar written in plain html, css and js, written with mobile in mind.

demo:
  https://elbasel.github.io/navBar/

install:
npm install @elbasel619/nav-bar

usage:

```
import navBar from '@elbasel619/navBar'

const bar = navBar.getNavElement([
{ icon0: 'path/to/icon', text0: string },
{ icon1: 'path/to/icon'', text1: string },
{ icon2: 'path/to/icon', text2: string },
{ icon3: 'path/to/icon', text3: string },
])

document.body.appendChild(bar)
```
