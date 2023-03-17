<!--badges-->
### IG Status
![qa-errs](https://img.shields.io/github/workflow/status/costateixeira/ig-badges/ig-build?label=Build%20status)

![issues](https://img.shields.io/github/issues/costateixeira/ig-badges)

![Custom Shield](https://img.shields.io/badge/Errors2-$(curl -s https://raw.githubusercontent.com/costateixeira/ig-badges/gh-pages/qa.json | grep -o '"errs":[0-9]*' | cut -d':' -f2)-red)

![Custom Shield](https://img.shields.io/badge/Errors1-$(curl -s https://raw.githubusercontent.com/costateixeira/ig-badges/gh-pages/qa.json | jq -r .errs)-red)

![Custom Shield](https://img.shields.io/badge/Errors3-85-red)

![Custom Shield](https://img.shields.io/badge/Errors4-33-red)


![Custom Shield](https://img.shields.io/badge/Errors-<script>(async()=>{let response=await fetch('https://raw.githubusercontent.com/costateixeira/ig-badges/gh-pages/qa.json');let json=await response.json();document.write(json.errs)})()</script>-red)

![Errors](https://img.shields.io/badge/Errors-33-red)
![Warnings](https://img.shields.io/badge/Warnings-416-yellow)

<!--/badges-->


Empty IG
---
This is an empty IG
<br> </br>
###
### Publication
This ImplementationGuide is published in the following locations:

Continuous Build: __http://build.fhir.org/ig/costateixeira/ig-badges/branches/main/index.html__  
Continuous Build: __http://costateixeira.github.io/ig-badges/branches/main/index.html__  
Continuous Build: __http://costateixeira.github.io/ig-badges/index.html__  
Canonical / permanent URL: 
<br> </br>

### Issues
Issues and change requests are managed here:  

Issues:  __https://github.com/costateixeira/ig-badges/issues__  
Kanban board:  __https://github.com/costateixeira/ig-badges/projects/1__  

---
