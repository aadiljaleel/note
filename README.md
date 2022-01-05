# note
Git + Markdown note taking app. Just fork, clone and note!

* add an alias to `note`
* `note` will open / create _README.md_
   * changes will automatically be committed (with date string) and pushed
* `note view` will just view the _README.md_ in nano
   * any changes on remote will note be pulled
   * changes will not be committed
   * `note view pull` will pull the changes and view the _README.md_ in nano
* `note edit` will open the _README.md_ in default text editor
* `note grep <text>` will run `grep` with `text` options on _README.md_