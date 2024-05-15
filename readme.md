# git functions
utilities for git bash terminal(windows)

<h1>Automate git push</h1>

```
git_auto() {
    # Automatizar git add .
    git add .

    # Solicitar al usuario el mensaje del commit
    echo "Ingrese el mensaje del commit:"
    read commit_message

    # Automatizar git commit -am "Mensaje del commit"
    git commit -am "$commit_message"

    # Automatizar git push
    git push
}
```



