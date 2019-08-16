# mithril-examples
Useful examples and flems from Mithril's gitter channel. See also the [links page](https://github.com/erikvullings/mithril-examples/blob/master/links.md) for other interesting projects.

## Routing

### Changing the routes

It is possible to completely change the navigation routes. [Example flems](https://flems.io/#0=N4IgZglgNgpgziAXAbVAOwIYFsZJAOgAsAXLKEAGhAGMB7NYmBvEAXwvW10QICsEqdBk2J4hcYgAIADhgDmMAIySAvJOAAdNJMkA3CDADuiSQAoAlKoB8WnTqymA5ABMIuxxVt37T6R8mOsgqKjuae2t6SDo4ARgCuxMT0-sD01FAQ1ADWJhbWUfgATrQJMPhwMMROAPRBMABMoewBSTLyMJKNYV7e0fGJyRTqaRnZuZYqVpJoRsWlcBbNjtSEGGgKknOMcKE9kuZarFpa4lJ19arqXvpG49Z70a7u4ZFRvv6B7V0vkX0JSWgUiNMjkzBMplgiiVGOVKjU6iFzEtWnVJIi9gc0Ec0Cd6BI2goAMyXTQRG7GMH3CI+FxuDx7Gl+IafImhH69Jz9AFAtDpEF3SYFLZlCpVRy1L5NZko9qSAAsu2p+0Ox15eLO7TlJOuBgpeUmDycT3pSsZHzqCu6presX+g2GvNGoP1EKhpVhYolwSlLVoBI6hMV3kx2NxaHxwrgyjUpJ04oRjhMCJ+8clSa+KpxavDUkjFxjXlT3vTRJTXoaif9cszWjAcV5xAg9Gms2h8DysaFbdMzlo1DiOAY+BitGcAE9meWQkM8yHVZDhT2+wORMPRxOAlP-JHFJjKCAKrBqI28Xg5QA2RAABjYHBAmBweHw1DgAho9EYzB4bAAulQMmgWQICgnCPjwWAQMQhCFNA+5xIU5A8CQxDSHAiDVNU9bSFkcjPrQWDVBBUEwVAAACij4BR56EZB0HQPg-D7sQY7SNwB7UDB0iiOwoFsTEr5wQheDIah6GYWg2G4XQBH8XA5H4AArJR1SyQxb7MaxeBwBxEBcb+rBAA).

```js
const routes1 = {
  '/page1': page1,
  '/page2': page2
}

const routes2 = {
  '/page1': page3,
  '/page2': page4
}

function newroutes() {
  m.route(document.body, '/page1', routes2)
}

m.route(document.body, '/page1', routes1)
```
