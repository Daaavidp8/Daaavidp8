Ordres basiques de git.

Git init->Per initzialitzar un repository git
git config --globa user.name "[Nombre]"->Indica el nom de la persona treballant en el projecte
git config --globa user.email "[Email]"->Indica el email de la persona treballant amb el projecte
git clone-> Per a descargar un projjecte y les seues versions
Git add->Afegir a l`area de preparacio el fitxer,posarem git add [nombre_archiu] o . si volem tots els archius
git commit-> Farem un commit,posarem -m per posar un nom al commit 
git status-> Visualitzem l`estat del commit
git branch [nom_branca]-> Per a crear una branca
git checkout [branca o hash de commit]->per a situarte en una branca o un commit fet anteriorment
git log->Mostra totes les versions del projecte de la branca actual
git log --graph --all-> pero vore les versions de totes les branques
git fetch->Descarga commits,archius y referencies d`un repositori remot al local sin sobrescriure res
git pull->El mateix que fa el fetch sobrescribint els archius.
git push->Pucha els archius al repositori remot
git merge->Fusiona 2 branques
