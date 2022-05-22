# Práctica 3. Git y GitHub

## Instrucciones
NOTA: algunos de los comandos son de windows

#### 1. Colócate dentro de tu carpeta practicas_genomica_computacional e inicializala como un repositorio local de git.

**Comando**
```
git init
```

**Salida**
```
Initialized empty Git repository in C:/Users/sin kik/Desktop/practicas_genomica_
computacional/.git/
```

#### 2. Agrega al área de espera todo el contendio de ésta carpeta.

**Comando**
```
git add ./*
```

**Salida**
```
C:\Users\sin kik\Desktop\practicas_genomica_computacional>git add ./*
warning: LF will be replaced by CRLF in mini_practicas/mp1_RoblesLara_MarianaJoc
elyn .ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in mini_practicas/mp2_RoblesLara_MarianaJoc
elyn.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/Parte III. Python-checkpoint
.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/data/filtered/barplot_data.t
xt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/data/filtered/cp_saccharomyc
es_genes.gff3.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/data/raw_data/saccharomyces.
fastq.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/data/raw_data/saccharomyces_
dna.fasta.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/data/raw_data/saccharomyces_
genbank.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/data/raw_data/saccharomyces_
genes.gff3.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/p2_Jocelyn_Robles-checkpoint
.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/scripts/Parte III. Python.ip
ynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in p2_ngs_bash/scripts/p2_Jocelyn_Robles.ip
ynb.
The file will have its original line endings in your working directory

C:\Users\sin kik\Desktop\practicas_genomica_computacional>
```


#### 3. Haz un primera confirmación de todo el contenido con el mensaje “Prácticas de Genomica Computacional”.

**Comando**
```
git commit -m "Prácticas de Genomica Computacional"
```

**Salida**
```
[master (root-commit) 235be49] Prácticas de Genómica Computacional
 14 files changed, 57472 insertions(+)
 create mode 100644 mini_practicas/mp1_RoblesLara_MarianaJocelyn .ipynb
 create mode 100644 mini_practicas/mp2_RoblesLara_MarianaJocelyn.ipynb
 create mode 100644 p1_dogma_central/p1_RoblesLara_MarianaJocelyn.py
 create mode 100644 p2_ngs_bash/Parte III. Python-checkpoint.ipynb
 create mode 100644 p2_ngs_bash/data/filtered/barplot_data.txt
 create mode 100644 p2_ngs_bash/data/filtered/cp_saccharomyces_genes.gff3
 create mode 100644 p2_ngs_bash/data/raw_data/saccharomyces.fastq
 create mode 100644 p2_ngs_bash/data/raw_data/saccharomyces_dna.fasta
 create mode 100644 p2_ngs_bash/data/raw_data/saccharomyces_genbank
 create mode 100644 p2_ngs_bash/data/raw_data/saccharomyces_genes.gff3
 create mode 100644 p2_ngs_bash/figures/barplot.png
 create mode 100644 p2_ngs_bash/p2_Jocelyn_Robles-checkpoint.ipynb
 create mode 100644 p2_ngs_bash/scripts/Parte III. Python.ipynb
 create mode 100644 p2_ngs_bash/scripts/p2_Jocelyn_Robles.ipynb

Warning: Your console font probably doesn't support Unicode. If you experience s
trange characters in the output, consider switching to a TrueType font such as C
onsolas!

```


#### 4. Crea un archivo .md en tu carpeta p1_dogma_central que describa qué hace tu programa. Si hay funciones dentro, qué hace cada función.

**Comando**
```
copy nul README.md
```

(escribimos la descripción del programa)


#### 5. Agrega la modificación de la instrucción anterior a tu área de éspera y luego haz la confirmación que lleve el siguiente mensaje “Descripcion de programa.”

**Comando**
```
git add README.md
```

**Comando**
```
git commit -m "Descripcion deprograma."
```

**Salida**
```
[master (root-commit) 48cc585] Descripción de programa
 1 file changed, 3 insertions(+)
 create mode 100644 README.md

Warning: Your console font probably doesn't support Unicode. If you experience s
trange characters in the output, consider switching to a TrueType font such as C
onsolas!

```


#### 6. Checa el historial de confirmaciones que has hecho.

**Comando**
```
git log
```

**Salida**
```
commit 48cc585b07be65dfa176ec02a87b186c10a7fb85 (HEAD -> master)
Author: mar <marianarobles17@ciencias.unam.mx>
Date:   Sat May 21 23:03:48 2022 -0500

    Descripción de programa

commit 224d0953ea9e457623910fe01ccfb26cf14d6c05
Author: mar <marianarobles17@ciencias.unam.mx>
Date:   Sat May 21 22:50:54 2022 -0500

    Prácticas de Genomica Computacional
```


#### 7. Checa en qué rama te encuentras.

**Comando**
```
git branch
```

**Salida**
```
* master
```


#### 8. Conecta éste repositorio local a tu repositorio remoto.
**Comando**
```
git remote add origin https://github.com/MarR0bles/GC---Pr-cticas---MarianaRobles.git
 git branch -M main 
git push -u origin main
```

**Salida**
```
Username for 'https://github.com': MarR0bles
Password for 'https://MarR0bles@github.com':
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 812 bytes | 50.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MarR0bles/GC---Pr-cticas---MarianaRobles.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'
```


#### 9. Crea un archivo README.md en tu repositorio remoto que contenga:
- A modo de encabezado: “Prácticas - Genómica computacional - 2022”
- Luego una línea en blanco.
- En la tercera línea tu nombre completo en negritas.
- OPCIONAL: Una descripción del contenido de éste repositorio.

**Comando**
```
copy nul "README.md" #Escribí manualmente el contenido
```

**Comando**
```
dir
```
**Salida**
```
22/05/2022  12:40 a. m.    <DIR>          .
22/05/2022  12:40 a. m.    <DIR>          ..
21/05/2022  06:45 p. m.    <DIR>          mini_practicas
21/05/2022  11:01 p. m.    <DIR>          p1_dogma_central
21/05/2022  06:48 p. m.    <DIR>          p2_ngs_bash
21/05/2022  06:42 p. m.    <DIR>          p3_git_gihub
22/05/2022  12:40 a. m.                 0 README.md
               1 archivos              0 bytes
               6 dirs  180,124,708,864 bytes libres
```


#### 10. Agrega las modificaciones de tu repositorio remoto a tu repositorio local.

**Comando**
```
git add README.md
git commit -m "README.md agregado"
git push
```

**Salida**
```
Username for 'https://github.com': MarR0bles
Password for 'https://MarR0bles@github.com':
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (3/3), 512 bytes | 50.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MarR0bles/GC---Pr-cticas---MarianaRobles.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'

```
