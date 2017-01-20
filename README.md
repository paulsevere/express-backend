# Snippet Sharer API

An API to store document metadata and allow users to have a cart and update it however they want.

---

## Links

The front-end is deployed here:<br>
https://paulsevere.github.io/snippet-sharer

The back-end is deployed here:<br>
https://snippet-server-app.herokuapp.com

The front-end repo can be found here:<br>
https://github.com/paulsevere/snippet-sharer

The back-end deployed repo can be found here:<br>
https://github.com/paulsevere/express-backend

## API end-points

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out/:id`        | `users#signout`   |
| GET    | `/snippets`               | `snippets#index`     |
| POST   | `/snippets`               | `snippets#create`     |
| PATCH  | `/snippets/:id`           | `snippets#update`     |
| DELETE | `/snippets/:id`           | `snippets#destroy`   |

---
![scissor](http://cliparting.com/wp-content/uploads/2016/07/Scissors-clip-art-free-clipart-images.gif)
## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
