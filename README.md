# campusciff    1  git config --global user.name "Daniel Serrano"
    2  git config --global user.email "daniserrano0404@gmail.com"
    3  git config --global credential.helper 'cache --timeout=36000'
    4  git config --global user.name "daserpel98"
    5  git config --global user.email "daniserrano0404@gmail.com"
    6  git config --global credential.helper 'cache --timeout=36000'
    7  pwd
    8  cd Downloads/
    9  mkdir pruebagit
   10  cd pruebagit
   11  git clone https://github.com/LuisJoseSanchez/aprende-java-con-ejercicios.git
   12  ls
   13  git pull
   14  cd aprende-java-con-ejercicios
   15  git pull
   16  cd ..
   17  git clone https://github.com/daserpel98/hola-mundo-en-java.git
   18  cd hola-mundo-en-java
   19  ls
   20  git pull
   21  cat readme.md
   22  touch HolaMundo.java
   23  nano HolaMundo.java
   24  git status
   25  git add . --all
   26  nano HolaMundo.java
   27  ls
   28  git status
   29  git add . --all
   30  git status
   31  git commit
   32  git commit -m
   33  git commit
   34  git commit -m "Añadido el fichero HolaMundo.java"
   35  git push
   36  nano .gitignore
   37  javac Holamundo.java
   38  cp Holamundo.java Holamundo.bak
   39  git add . --all
   40  git commit -m "Añadido archivo ignorado"
   41  git push
   42  git log
   43  cat HolaMundo.java
   44  git tag -a v1.0 -m 'Versión 1.0 - "Hola mundo" clásico'
   45  nano Holamundo.java
   46  git tag -a v1.1 -m 'Versión 1.1 - "Hola mundo" comentao'
   47  git add . --all
   48  git commit -m "Comentaçao"
   49  git push
   50  git push --tags
   51  cat HolaMundo.java
   52  git tag -a v1.0 -m 'Versión 1.0 - "Hola mundo" clásico'
   53  git tag -a v1.2 -m 'Versión 1.2 - "Hola mundo" con comentario'
   54  git add . --all
   55  git commit -m "Comentaçao"
   56  git push --tags
   57  nano HolaMundo.java
   58  git tag -a v1.3 -m 'Versión 1.3 - "Hola mundo" v3'
   59  git add . --all
   60  git commit -m "Hola mundo v3"
   61  git push
   62  git tag hel
   63  git tag
   64  git tag -d v1.0
   65  git push --tags
   66  git tag
   67  git tag
   68  git tag -d v1.1
   69  git  tag -d hel
   70  git push --delete origin tag v1.0
   71  git push -d origin tag v1.1
   72  git push -d origin tag hel
   73  git checkout -b experimentocolores
   74  ls
   75  rm *.bak
   76  ls
   77  git checkout master
   78  ls
   79  git checkout experimentacolores
   80  git checkout experimentocolores
   81  ls
   82  git status
   83  git add . --all
   84  git commit -m "Colores definidos"
   85  git push --set-upstream origin experimentocolores
   86  cp Holamundo.java HolaMundoExperimentocolores
   87  git checkout master
   88  cp Holamundo.java HolaMundo.master
   89  git checkout experimentocolores
   90  git add . --all
   91  git commit -m "backup experimetno"
   92  git push
   93  git checkout master
   94  git push --set-upstream origin master
   95  git checkout experimentocolores
   96  rm HolaMundo.master
   97  ls
   98  git add . --all
   99  git commit -m "Eliminado master"
  100  git push --set-upstream origin experimentocolores
  101  git checkout master
  102  cp Holamundo.java HolaMundo.master
  103  git add . --all
  104  git commit -m "Añado Hola mundo master"
  105  git push --set-upstream origin master
  106  git checkout master
  107  git merge experimentocolores
  108  git push
  109  quit
  110  git clone https://github.com/daserpel98/pulpogato.git
  111  rm -rf pulpogato
  112  cd Documenst
  113  cd Documents
  114  ls
  115  cd RepoActividades
  116  ls
  117  cd campusciff/
  118  ls
  119  history
  120  history >> README.md
