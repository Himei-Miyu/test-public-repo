# Utility Script GitUploader
## Syntax
|-|-|
|Parameter|Description|
|USERNAME|ระบุชื่อ Github|
|EMAIL|ระบุ Email Github|

## How to use

```bash
eval "$(curl -sL https://himei.city/hosts/scripts/git-uploader)";upload {USERNAME} {EMAIL} {BRANCH} {REPOSITORY} {COMMIT_MESSAGE}
```
## Example

```bash
eval "$(curl -sL https://himei.city/hosts/scripts/git-uploader)";upload example example@gmail.com main example-project "First Commit"
```
