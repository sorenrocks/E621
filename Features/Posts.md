## Table Of Contents
- [Index](README.md)
- [Future Plans](FuturePlans.md)
- [Artists](Artists.md)
- [Pools](Pools.md)
- **Posts**
- [Post Sets](PostSets.md)
- [Tags](Tags.md)
- [User Feedback](UserFeedback.md)
- [Users](Users.md)
- [Wiki Pages](WikiPages.md)

<hr>

|            Feature            | Implemented |         Method         |
|:-----------------------------:|:-----------:|:----------------------:|
|           Get By ID           |      ✔️      |       `posts.get`      |
|          Get By Name          |      ✔️      |    `posts.getByName`   |
|             Search            |      ✔️      |     `posts.search`     |
|           Create[^1]          |      ✔️      |     `posts.create`     |
|           Modify[^1]          |      ✔️      |     `posts.modify`     |
|         Delete[^1][^3]        |      ✖️      |           N/A          |
|        Approve[^1][^3]        |      ✖️      |           N/A          |
|       Unapprove[^1][^3]       |      ✖️      |           N/A          |
|        Destroy[^1][^5]        |      ✖️      |           N/A          |
| Regenerate Thumbnails[^1][^3] |      ✖️      |           N/A          |
|   Regenerate Videos[^1][^3]   |      ✖️      |           N/A          |
|           Revert[^1]          |      ✔️      |     `posts.revert`     |
|       Search History[^1]      |      ✔️      |  `posts.searchHistory` |
|            Vote[^1]           |      ✔️      |      `posts.vote`      |
|        Add Favorite[^1]       |      ✔️      |   `users.addFavorite`  |
|      Remove Favorite[^1]      |      ✔️      | `users.removeFavorite` |

[^1]: Requires Authentication
[^2]: Requires Privileged
[^3]: Requires Janitor
[^4]: Requires Moderator
[^5]: Requires Admin