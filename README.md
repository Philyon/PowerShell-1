# PowerShell-1

## Commandes Bash et leur équivalent Powershell

| **Commande Bash** | **Commande Powershell** | **Description**                  |
|--------------------|--------------------------|----------------------------------|
| `cp (copy)`              | `Copy-Item`             | Copier des fichiers ou dossiers. |
| `rm (remove)`              | `Remove-Item`           | Supprimer des fichiers ou dossiers. |
| `cd (change directory)`              | `cd (change directory)`                    | Changer de répertoire.           |
| `mkdir (make direction)`           | `mkdir (make direction)`                 | Créer un nouveau dossier. |
| `man (manual)`             | `Get-Help`              | Afficher l'aide pour une commande. |
| `history`         | `Get-History`           | Afficher l'historique des commandes. |
| `alias`           | `Set-Alias`             | Créer ou modifier un alias.      |
| `cat (concatenate)`             | `cat (concatenate)`                   | Lire et afficher le contenu d'un fichier. |

## Les commandes utilisées lors de la quête

- copy-item varpath.sh varpathdupath.sh
- remove-item varpathdupath.sh
- cd Virtual Machines
- cd "Virtual Machines"
- ls
- mkdir Dossier-PowerShell
- remove-item Dossier-PowerShell
- Get-Help ls
- Get-Help mkdir
- Get-Help cp
- Gel-Help cd
- Get-History
- cd ..
- Get-Content varpath.sh
- Set-Alias -Name gc -Value Get-Content
- Get-Alias
- gc varpath.sh
- gc sti_trace.log
- gc Sti_Trace.log
- gc varpath.sh
- gc varpath.py
- gc Unix_commands.md
- history
- cat varpath.sh
