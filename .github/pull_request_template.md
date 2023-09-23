<!--- Please fill the necessary details below -->
## Purpose / Description
_Describe the problem or feature and motivation_

## Fixes
Fixes _Link to the issues._

## Approach
_How does this change address the problem?_

## How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration (SDK version(s), emulator or physical, etc)

## Learning (optional, can help others)
_Describe the research stage_

_Links to blog posts, patterns, libraries or addons used to solve this problem_

## Checklist
_Please, go through these checks before submitting the PR._

- [ ] You have a descriptive commit message with a short title (first line, max 50 chars).
- [ ] You have commented your code, particularly in hard-to-understand areas
- [ ] You have performed a self-review of your own code
- [ ] UI changes: include screenshots of all affected screens (in particular showing any new or changed strings)
- [ ] UI Changes: You have tested your change using the [Google Accessibility Scanner](https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.auditor)

Claro, aqui está um trecho que você pode incluir no arquivo `README.md` do seu projeto para orientar os contribuidores sobre como criar um Pull Request (PR) seguindo as convenções de nomeclatura:

---

## Contribuindo para o Projeto

## Nomeclatura das Branches

Ao criar uma nova branch, por favor, siga as nossas convenções de nomeclatura:

- **Feature Branches**: `feature/<ID_do_Ticket>-<Descricao_Resumida>`
- **Fix Branches**: `fix/<ID_do_Ticket>-<Descricao_Resumida>`
- **Release Branches**: `release/<Versao>`
- **Hotfix Branches**: `hotfix/<ID_do_Ticket>-<Descricao_Resumida>`
- **Support Branches**: `support/<ID_do_Ticket>-<Descricao_Resumida>`

Isso nos ajuda a manter um histórico de código limpo e fácil de seguir.


### Criando Pull Requests

Ao criar um Pull Request, por favor, siga as nossas convenções de nomeclatura para facilitar o rastreamento e revisão.

#### Nomeclatura do Título do PR
```
<tipo>: [<Identificador do Ticket>] <Descrição>
```

- **`<tipo>`**: Este é o tipo de mudança que você está propondo. Pode ser um dos seguintes:
    - `feature`: Para novas funcionalidades ou melhorias.
    - `fix`: Para correções de bugs.
    - `release`: Para preparações de novas versões.
    - `hotfix`: Para correções urgentes.
    - `support`: Para outras mudanças que não se encaixam nas categorias acima.

- **`<Ticket>`**: Este é o identificador do ticket relacionado à sua mudança.

- **`<Descrição>`**: Uma breve descrição do que o PR faz.

#### Exemplos de Títulos de PR

- `feature: [SQT-123] Add Login Button`
- `fix: [SQT-124] Resolve Memory Leak`
- `release: [SQT-125] Prepare for Version 1.0`
- `hotfix: [SQT-126] Fix Security Vulnerability`
- `support: [SQT-127] Update Documentation`

