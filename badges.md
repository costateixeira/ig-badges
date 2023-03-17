### IG Status
![qa-errs](https://img.shields.io/github/workflow/status/__GH_OWNER__/__GH_REPO__/ig-build?label=Build%20status)

![issues](https://img.shields.io/github/issues/__GH_OWNER__/__GH_REPO__)

![Custom Shield](https://img.shields.io/badge/Errors-$(curl -s https://raw.githubusercontent.com/__GH_OWNER__/__GH_REPO__/gh-pages/qa.json | jq -r .errs)-red)
![Custom Shield](https://img.shields.io/badge/Errors-$(curl -s https://raw.githubusercontent.com/costateixeira/ig-badges/gh-pages/qa.json | grep -o '"errs":[0-9]*' | cut -d':' -f2)-red)

![Custom Shield](https://img.shields.io/badge/Errors-85-red)

![Errors](https://img.shields.io/badge/Errors-__ERRS__-red)
![Warnings](https://img.shields.io/badge/Warnings-__WARNINGS__-yellow)


[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
