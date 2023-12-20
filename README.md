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