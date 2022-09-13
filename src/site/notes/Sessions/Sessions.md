---
{"dg-publish":true,"permalink":"/sessions/sessions/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Sessions
 
```dataview
TABLE file.cday as Date, num, highlights
FROM "Sessions"
WHERE file.name != "Sessions"
SORT file.cday DESC
```
