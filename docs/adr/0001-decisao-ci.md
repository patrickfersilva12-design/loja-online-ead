# ADR 001: Uso do GitHub Actions pata Integração Contínua

## Contexto
O projeto precisa rodar testes automaticamente a cada Pull Request.
Existem várias ferramentas de CI no mercado (Jenkins, CircleCI,GitHub Actions).

## Decisão
Vamos usar o GitHub Actions.

## Motivo
Já hospedamos o código no GitHub, então não é preciso integrar com 
outra plataforma. É graituito para repositórios públicos e a
configuração fica no próprio reposiitório, versionada junto com o 
código

## Consequências
Ficamos dependentes do ecossistema GItHub. Se um dia migrarmos de
plataforma de hospedagem, o pipeline de CI precisará se recriado.