# readme-tag

Tags an Azure Resource Group with the README URL of the repository.

## Usage

Provide the resource group name, the branch name (default: main), and the name of the
file to check (default: README.md). If the file is found, the resource group is tagged
with the tag readme with the URL of the file.

```github-actions
- name: Tag with README
  uses: rancorm/readme-tag@v1
  with:
    resource-group: "my-resource-group"
    branch: "main"
    check-file: "README.md"
```
