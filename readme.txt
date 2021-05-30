
#Configurações iniciais
git config --global user.name "Jesse James"
git config --global user.email "jj@jsoft.com.br"
git config --list

#Iniciar um repositório
git init 

#Mostrar o status dos arquivos
git status

#Adicionar ao stage
git add .

#Comitar os arquivos que estiverem no stage
git commit -m "Nome do commit"

#Aula 13
$ git diff
diff --git a/readme.txt b/readme.txt
index 15b8aa0..20e9cc5 100644
--- a/readme.txt
+++ b/readme.txt
@@ -16,6 +16,8 @@ git add .
 #Comitar os arquivos que estiverem no stage
 git commit -m "Nome do commit"

git diff --cached
diff --git a/aula 13.txt b/aula 13.txt
new file mode 100644
index 0000000..d73a9a6
--- /dev/null
+++ b/aula 13.txt
@@ -0,0 +1 @@
+Só um texto pra ser apagado
\ No newline at end of file
diff --git a/readme.txt b/readme.txt
index 15b8aa0..20e9cc5 100644
--- a/readme.txt
+++ b/readme.txt
@@ -16,6 +16,8 @@ git add .
 #Comitar os arquivos que estiverem no stage
 git commit -m "Nome do commit"
 
 Modificado no github






 
