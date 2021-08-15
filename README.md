﻿| [Live User Filter](https://github.com/lana-20/50Projects50Days/tree/main/LiveUserFilter) | [Live Demo](https://lana-20.github.io/live-user-filter/) |
 |----|----|

In this project, I am creating a live user filter where I am fetching a bunch of users from the Random User Generator API (https://randomuser.me/).
I fetch them, put them in the user list and then filter these users. If I type an "s", any user that has an "s" in their name or location is going to show.
If I type "sil", the only user that matches is Silke Jørgensen. And if I delete characters, it still continues to filter and match whatever I put in the search field.
I am dealing with the fetch API. I am using async/await, as opposed to .then syntax for fetch, which returns a promise.
I am creating the UI style with CSS, then fetching the data and implementing the filtering.

