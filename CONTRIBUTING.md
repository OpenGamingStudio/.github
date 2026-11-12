# Contribuer à OpenGamingStudio

Merci de votre intérêt ! Ces règles s'appliquent à tous les dépôts publics de l'organisation (LifeCraft, QuizDown, SnakeIncremental…). Merci aussi de respecter notre [code de conduite](CODE_OF_CONDUCT.md).

## Branches

- Nommage : `feat/<sujet-court>`, `fix/<sujet-court>`, `docs/<sujet-court>`, `chore/<sujet-court>`.
- Toujours créée depuis `main`. Aucun push direct : `main` est protégé (PR obligatoire, pas de force push).

## Commits

- [Conventional Commits](https://www.conventionalcommits.org/fr/) : `feat:`, `fix:`, `docs:`, `test:`, `chore:`.
- Message à l'impératif, 72 caractères maximum.
- Une PR = un sujet.

## Tests et style

- Tout correctif (`fix`) s'accompagne d'un test de non-régression ; toute fonctionnalité (`feat`) a ses tests.
- Lint et tests verts avant d'ouvrir la PR.
- Respectez le formateur et le linter du dépôt ; pas de code mort.

## Revue et fusion

- Chaque PR est relue par Rémi Review ; sa relecture est obligatoire avant tout push sur une branche partagée, avant l'ouverture de la PR et avant la fusion. Son accord écrit est requis à chacune de ces étapes.
- La fusion sur `main` est faite uniquement par Yann Deploy, avec les accords écrits de Rémi et de Victor.

## Documentation des bibliothèques (Context7)

Toute API de bibliothèque utilisée est vérifiée avec Context7 ; mentionnez-le dans la PR.

## Sécurité

- Aucun secret, clé ni donnée personnelle dans un fichier, un commit, une issue ou une PR.
- Signalez toute vulnérabilité en privé via les GitHub Security advisories (onglet « Security » → « Report a vulnerability » du dépôt), jamais dans une issue publique.

## Contributeurs externes

1. **Forkez** le dépôt et clonez votre fork.
2. Pour un gros changement, **ouvrez d'abord une issue** afin d'en discuter avant de coder.
3. Créez une branche `feat/…` ou `fix/…` depuis `main` dans votre fork.
4. Respectez les règles ci-dessus (commits, tests, lint, aucun secret).
5. Ouvrez une **PR avec le modèle** fourni, en cochant la checklist.
6. En contribuant, vous acceptez que votre contribution soit publiée sous **licence MIT**, comme le reste du projet.
7. La PR est triée par Léa ou Victor (direction du studio), puis relue par Rémi Review ; la fusion suit les règles de la section « Revue et fusion ».
