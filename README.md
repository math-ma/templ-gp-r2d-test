# templ-gp-r2d-test
quarto gp render to docs  (template ?)



---

`.gitignore`
`.nojekyll`



`a-glavnyj_smyslovoj-fajl_edit_template.qmd`	- главный смысловой файл, откуда все вызывается. В файле index.html  автоматом ставится перенаправление на него

`_file-to-include_nohtml-output_index-mp24-p2.qmd`
вставляется через includе  стандартно.     
html  автоматом не создается



`_inserted_as_code_md.qmd`
`_quarto.yml`
`nounderscore_name.qmd`	- вставляется через includе  стандартно.     
html  создается - НЕ рекомендуется



`ostrova-2-link.qmd`
`ostrova-2-link_md.md`	- вставляются как ссылки на внешний html
Почему не путается с основным файлом ? Загадка !
В алфавитном порядке ?



`README.md`
