<title>useNavigate</title>

##### `useNavigate` gives you an object containing the path params of the current route

<div class="text-xl">

```ts twoslash
import { useNavigate } from "@solidjs/router";
// ---cut---
const params = useNavigate();
```

</div>

- [Usage](#usage)

  - [Reading `id` param for route `/users/:id`](#accessing-id-param-for-route-users-id)
  - [Reading both `id` and `project` params for route `/users/:id/projects/:project`](#accessing-id-param-for-route-users-id)
  - [Fetching data based on the path params](#example)
  - [Show helpful error message for catch-all/404 routes](#example)

- [Reference](#reference)

  - [`useNavigate()`](#hello-world)

- [Troublehooting](#troublehooting)
