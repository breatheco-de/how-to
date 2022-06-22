# Contribute to the How To database

All articles are inside the `./content` folder with the following path structure: `./content/<category>/<topic_cluster>/<keyword>.<lang>.md`

> Please do not create new files or folders, only work with files that currently exist and have `[unnasigned]` on there names.


1. Look for articles with name starting with [unassigned], for example: 

```
./content/devops/how-to-install-nvm/[unassigned]how-to-install-nvm-on-windows.es.md
```

2. Open the file, edit the frontmatter.authors array to add yourself into it.

```
---

authors: ["your_username"]

---
```

3. Rename the file with [writing] instead of [unassigned] and start working on the article.

```
./content/devops/how-to-install-nvm/[writing]how-to-install-nvm-on-windows.es.md
```

4. Once you are ready, rename the file again but now to [draft].

```
./content/devops/how-to-install-nvm/[draft]how-to-install-nvm-on-windows.es.md
```

5. Notify your editor and wait for feedback or approval.
