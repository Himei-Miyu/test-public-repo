# Utility Script GitUploader
## Syntax
| Parameter | Description      |
|-----------|------------------|
| `USERNAME`  | ระบุชื่อ Github     |
| `EMAIL`     | ระบุ Email Github |
| `BRANCH` | ระบุสาขาใน repo |
| `REPOSITORY` | ระบุชื่อ repo |
| `COMMIT_MESSAGE` | ระบุข้อความ commit |

## How to use

```bash
eval "$(curl -sL https://himei.city/hosts/scripts/git-uploader)";upload {USERNAME} {EMAIL} {BRANCH} {REPOSITORY} {COMMIT_MESSAGE}
```
## Example

```bash
eval "$(curl -sL https://himei.city/hosts/scripts/git-uploader)";upload example example@gmail.com main example-project "First Commit"
```
