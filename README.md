<header>

# Git & VS Code

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="170px" />

_Apprends le workflow Git utilisé au quotidien dans le club, depuis ton ordinateur._

</header>

## Bienvenue

Ce tutoriel fait suite à **[GitHub Basics](https://github.com/ENSTARobotics/tutorial-github-basics)**.

Dans le premier cours, tu as appris le modèle mental depuis le navigateur : dépôt, branche, commit, pull request, review et merge.

Ici, tu vas refaire le même cycle comme on le fait réellement sur un projet du club :

```text
GitHub
  ↓ clone
ordinateur
  ↓
VS Code + terminal
  ↓
branche locale
  ↓
modification
  ↓
staging
  ↓
commit local
  ↓ push
GitHub
  ↓
pull request
  ↓
merge
  ↓
git pull
ordinateur à jour
```

## Ce que tu vas apprendre

Pendant l'exercice, tu vas apprendre à :

- copier un dépôt GitHub sur ton ordinateur avec `git clone` ;
- voir l'état de ton travail avec `git status` ;
- comparer précisément tes modifications avec `git diff` ;
- choisir les changements qui entreront dans le prochain commit avec `git add` ;
- créer des commits locaux et lire leur historique ;
- annuler proprement une modification locale avec `git restore` ;
- créer une branche de travail avec `git switch` ;
- comprendre comment ton dépôt local est relié à GitHub ;
- utiliser le panneau **Source Control** et le graphe Git de VS Code ;
- effectuer le cycle complet jusqu'à une pull request et son merge.

Les termes comme **remote**, **origin**, **staging area**, **upstream** ou **HEAD** seront définis au moment où tu les rencontres.

## Prérequis

Avant de commencer :

1. avoir un compte GitHub ;
2. avoir **Git** installé sur ton ordinateur ;
3. avoir **Visual Studio Code** installé ;
4. idéalement avoir terminé [GitHub Basics](https://github.com/ENSTARobotics/tutorial-github-basics).

Tu peux vérifier Git avec :

```bash
git --version
```

Le cours est conçu pour être réalisé sur **ta machine locale**, pas dans Codespaces.

## Démarrer

Crée un nouveau dépôt à partir de ce **dépôt modèle**.

[![Commencer le cours](https://img.shields.io/badge/Commencer%20le%20cours-%E2%86%92-1f883d?style=for-the-badge&logo=git&labelColor=197935)](https://github.com/new?template_owner=ENSTARobotics&template_name=tutorial-git-vscode&owner=%40me&name=tutorial-git-vscode&description=Tutoriel%20interactif%20%3A%20apprendre%20Git%20en%20ligne%20de%20commande%20avec%20VS%20Code&visibility=public)

Après la création du dépôt :

1. attends une vingtaine de secondes ;
2. actualise la page ;
3. ouvre l'Issue créée automatiquement par Mona ;
4. suis ensuite les instructions depuis ton ordinateur.

> [!NOTE]
> Les étapes locales comme `git status` ou `git diff` ne quittent pas ton ordinateur. Le bot ne peut donc pas les espionner. Il valide uniquement les jalons qui arrivent réellement sur GitHub, par exemple la publication d'une branche, un commit poussé ou une pull request.

<details>
<summary>Le cours ne démarre pas ?</summary>

Ouvre l'onglet **Actions** et vérifie le workflow **Step 0**. GitHub Actions est le système d'automatisation utilisé par le bot du cours.

</details>

---

Inspiré de [GitHub Skills - Introduction to Git](https://github.com/skills/introduction-to-git), de la documentation Git officielle et de la documentation Source Control de VS Code.
