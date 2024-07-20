# readme-tag

Tags an Azure Resource Group with the README URL of the repository.

## Usage

```github-actions
- name: Tag with README
  uses: rancorm/readme-tag@v1
  with:
    resource-group: 'my-resource-group'
    repository: 'my-repository'
    token: ${{ secrets.GITHUB_TOKEN }}
```
