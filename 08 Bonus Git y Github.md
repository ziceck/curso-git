# comandos y recursos colaborativos en Git y Github

- **git shortlog -sn** = muestra cuantos commit han hecho cada miembros del equipo.
- **git shortlog -sn --all** = muestra cuantos commit han hecho cada miembros del equipo hasta los que han sido eliminado
- **git shortlog -sn --all --no-merge** = muestra cuantos commit han hecho cada miembros quitando los eliminados sin los merges
- **git blame ARCHIVO** = muestra quien hizo cada cosa linea por linea
- **git COMANDO --help** = muestra como funciona el comando.
- **git blame ARCHIVO -Llinea_inicial,linea_final**= muestra quien hizo cada cosa linea por linea indicándole desde que linea ver ejemplo -L35,50
- **git branch -r **= se muestran todas las ramas remotas
- **git branch -a** = se muestran todas las ramas tanto locales como remotas