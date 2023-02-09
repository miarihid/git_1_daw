# git_1_daw
git clone https://github.com/miarihid/git_1_daw
git add README.md
git commit -m "commit inicial"
git push origin main
touch privado.txt
mkdir privada
touch .gitignore
echo "privado.txt" >> .gitignore
echo "privada/" >> .gitignore
git add .gitignore
touch 1.txt
git add 1.txt
git commit -m "añadir .gitignore y 1.txt"

| Compañero | Enlace |
| --- | --- |
| Compañero 1 | [Compañero 1](google.com) |
| Compañero 2 | [Compañero 2](google.com) |
| Compañero 3 | [Compañero 3](google.com) |

git branch v0.2
git checkout v0.2
git add 2.txt
git push origin v0.2
git checkout main
git merge v0.2
echo "hola" > 1.txt
git add 1.txt
git commit -m "commit en main para conflicto"
git checkout v0.2
echo "adios" > 1.txt
git add 1.txt
git commit -m "commit en v0.2 para conflicto"
