# Configuração do R no VSCODE


Step 1:

a) Instale o httpgd do CRAN ou github.
 - Do CRAN:
   `install.packages("httpgd")`

 - Do GitHub:
   `devtools::install_github("nx10/httpgd")`

b) Install languageserver:

`install.packages("languageserver")`

Step 2:

Install R extension for vscode
https://marketplace.visualstudio.com/items?itemName=REditorSupport.r

Step 3:

From vscode setting, select R > Plot: Use httpgd to use for R plot.

`setting.json`
` "r.plot.useHttpgd": true,`

They have done a amazing job with R extension. We can view data.frame and list in a separate data viewer in vscode.

# Rmarkdown

Pandoc: https://pandoc.org/installing.html

baixar versão do https://github.com/jgm/pandoc/releases/tag/3.1.11

qual versão baixar: `pandoc-3.1.11-windows-x86_64.msi`
 baixar o tipo .msi para facilitar a instalação.

verifique o local onde foi instalado. Normalmente fica na pasta
`C:\Users\czarg\AppData\Local\Pandoc`
