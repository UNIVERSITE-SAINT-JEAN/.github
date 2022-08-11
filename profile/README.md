<a name="readme-top"></a>

<!-- PROJECT LOGO DE USI @DEVZEBS-->
<br />
<div align="center">
   <a href="https://github.com/NGcodeX">
    <img src="https://github.com/UNIVERSITE-SAINT-JEAN/.github/blob/master/Ssfdsfans%20titre.png?raw=true" alt="Logo" width="200" height="200">
  </a>

  <h3 align="center">UNIVERSITE SAINT JEAN GITHUB</h3>

  <p align="center">
    Bienvenue DEV j'espere que vous êtes en pleine forme! Admin:<br> <a href="https://github.com/PILOTEZEBS">NGUENA ZEBS»</a> /ETUDIANT A USJ
    <br/>
    <a href="https://github.com/PILOTEZEBS"><img src="https://avatars.githubusercontent.com/u/94785948?v=4" width="64px"/></a><br>
    <a href="https://institutsaintjean.org/" target=_blank><strong>Explorer le Site USJ »</strong></a>
    <br />
    <br />
    <a href="https://institutsaintjean.org/a-propos/">A Propos </a>
    ·
    <a href="https://institutsaintjean.org/cycle-ingenieur/">Formation</a>
    ·
    <a href="https://institutsaintjean.org/stage-et-employabilite/">Stage et employabilité</a>
  </p>
</div>

<img src="https://github.com/UNIVERSITE-SAINT-JEAN/.github/blob/master/profile/Github%20Saint%20Jean.png?raw=true">

<!-- TABLE OF CONTENTS @DEVZEBS USJ-->
<details>
  <summary>Table de Projets</summary>
  <ol>
    <li>
      <a href="#about-the-project">Commencer</a>
      <ul>
        <li><a href="#built-with"></a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started"></a>
      <ul>
        <li><a href="#prerequisites"></a></li>
      </ul>
    </li>
    <ul>
    <li><a href="#roadmap">Pages</a></li>
    <li><a href="#contributing"></a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments"></a></li>
    </ul>
  </ol>
</details>


## Commencer

Tout d'abord, nous tenons à vous remercier d'avoir pris le temps de contribuer et de faire de ce projet un meilleur projet !

Ici, nous avons un ensemble d'instructions et de lignes directrices pour réduire les malentendus et rendre le processus de contribution à `profile-USJ` aussi fluide que possible.

Nous espérons que ce guide rendra le processus de contribution clair et répondra à toutes vos questions.

### Langue

Veuillez, tout en contribuant ou en interagissant de quelque manière que ce soit dans les projets USJ,  l'**anglais** ou le **Francais**.

#### For native English speakers

For English speakers, try to use simple words and phrases to allow others to understand when commenting on code, on Gists or on issues.

Try to encourage newcomers to USJ github to voice their opinions and get them into the code hotspot😎.


## Soumettre une issues

- Veuillez rechercher des problèmes similaires avant d'en ouvrir un nouveau ;
- Utilisez l'un des modèles de problèmes correspondants ;
- Utilisez un titre clair et descriptif ;
- Incluez autant d'informations que possible en remplissant le problème fourni
  modèle;
- La plupart du temps, la meilleure façon de signaler un problème est un test qui échoue le prouvant.


#### Environnement de développement

Utiliser les outils de développement qui vous convient et fait nous un `pull-request- USJ`.

## S'engager

Un message de validation peut être composé d'un **en-tête**, d'un **corps** et d'un **pied de page**. L'en-tête est la seule partie obligatoire et se compose d'un type et d'un sujet. Le corps est utilisé pour décrire complètement le changement. Le pied de page est l'endroit où référencer tous les problèmes ou demandes d'extraction liés au commit. Cela dit, nous terminons avec un modèle comme celui-ci :

```
<emoji> <type>: <subject>

[optional body]

[optional footer]
```

Pour vous assurer qu'un commit est valide et facile à lire, vérifiez les points suivants :

- L'en-tête (première ligne) est la seule partie obligatoire du message de validation ;
- Le corps et le pied de page sont facultatifs mais leur utilisation est fortement encouragée ;
- L'en-tête doit contenir :
  - Un type avec votre emoji respectif :
    - Doit être en minuscule;
    - Doit être l'un des suivants :
      - ⚡ **corvée** : Une modification qui ne corrige pas de bug ni n'ajoute de fonctionnalité ;
      -    **ci** : Un changement de CI ;
      - 📖 **docs** : modification ou correction de la documentation ;
      - ✨ **feat** : Une nouvelle fonctionnalité ;
      - 🐛 **correction** : une correction de bug ;
      - 🤖 **test** : Un changement lié au test.
      -    **peluche** : Un changement lié au test.
  - A subject:
    - Must be lowercase;
    - Must be limited to 50 characters or less;
    - Must omit any trailing punctuation;
    - Avoid camel case ("my awesome method" not "myAwesomeMethod").
- The body:
  - Must have a leading blank line;
  - Each line must be limited to 72 characters or less;
  - Must be capitalized.
- The footer:
  - Must have a leading blank line;
  - Each line must be limited to 72 characters or less;
  - If needed, reference to issues and pull requests must be made here in the last line.

You also should follow these general guidelines when committing:

- Use the present tense ("add feature" not "added feature");
- Use the imperative mood ("move cursor to..." not "moves cursor to...");
- Try to answer the following questions:
  - Why is this change necessary?
  - How does it address the issue?
  - What side effects (if any) does this change may have?

Example of a commit message:

```
✨ type: commit message style guide for git

Oftentimes a subject by itself is sufficient. When it's not, add a
blank line (this is important) followed by one or more paragraphs hard
wrapped to 72 characters. Git is strongly opinionated that the author
is responsible for line breaks; if you omit them, command line tooling
will show it as one extremely long unwrapped line. Fortunately, most
text editors are capable of automating this.

Issues and pull request can be referenced on the footer: #3 #12
```

### Why all these rules?

We try to enforce these rules for the following reasons:

- Communicating in a better way the nature of changes;
- Triggering build and publish processes;
- Automatically determining a semantic version bump (based on the types of commits);
- Making it easier for people to contribute, by allowing them to explore a more structured commit history.

## Submitting a pull request

Before submitting a pull request, please make sure the following is done:

- [Fork](https://help.github.com/en/articles/fork-a-repo) the repository and create your branch from `main`.
  - Example: `feat/my-awesome-feature` or `fix/annoying-bug`;
- Run `yarn` in the repository root;
- Ensure the test suite passes;
- Ensure your commit is validated;

