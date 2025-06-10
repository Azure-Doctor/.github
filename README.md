# 👋 Salut, moi c’est Azure Doctor

Bienvenue dans mon espace GitHub — là où je partage **des outils concrets**, des **kits de démarrage**, des **scripts automatisés** et des idées pour **simplifier Azure au quotidien**.  
Tu galères avec AVD, RDS, les scripts CLI ou l’infra as code ? Ce dépôt est fait pour toi.



##  Ma mission

Rendre l’Azure technique **plus clair, plus humain, plus actionnable**.

-  Des Starter Kits prêts à l’emploi
-  Des scripts simples, commentés, efficaces
-  Des outils pour monter un environnement Azure de zéro
-  Des démos reproductibles et testées en live
- 💬 Des échanges clairs, pas de jargon inutile



## 📦 Mes Starter Kits

Voici ce que tu peux déjà tester, cloner, améliorer :

| Projet | Description | Lien |
|--------|-------------|------|
| `rds-starter-kit-cli` | Déploiement complet RDS sur Azure en PowerShell CLI | 👉 [Voir le dépôt](https://github.com/AzureDoctor/rds-starter-kit-cli) |
| `avd-starter-kit-cli` | Script Bash pour déployer un environnement Azure Virtual Desktop de bout en bout | 👉 [Voir le dépôt](https://github.com/AzureDoctor/avd-starter-kit-cli) |
| `toolbox-scripts` | Scripts PowerShell utiles (DNS, AADDS, join domain, etc.) |  Bientôt dispo |

➡️ Chaque kit contient :
- Un script principal (`deploy.sh` ou `deploy.ps1`)
- Une documentation claire (`README`, schéma, exemples)
- Un design cohérent
- Des conventions de nommage adaptées



##  Comment utiliser mes scripts

- Pas besoin d’être expert : tout est documenté étape par étape
- Il suffit de cloner un dépôt, lire le README, et lancer `deploy-*.sh` ou `deploy-*.ps1`
- Chaque ressource déployée suit une logique propre, modulaire, et facilement nettoyable

```bash
git clone https://github.com/AzureDoctor/avd-starter-kit-cli.git
cd avd-starter-kit-cli/cli
./deploy-avd.sh
