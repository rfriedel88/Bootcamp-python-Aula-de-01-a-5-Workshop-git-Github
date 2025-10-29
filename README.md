# Repositório do Bootcamp de python referente as aulas 01 a 05 + Workshop git Github

---
 Este repositório foi construído a partir das aulas da [Jornada de Dados](https://www.linkedin.com/company/jornadadedados/posts/?feedView=all) onde acrescentei links, referencias das documemntações mencionadas na aula  e demais referêcias que encontrei pela  net.

Repositórios da Jornada:  

- [Workshop git & Github](https://github.com/lvgalvao/data-engineering-roadmap/tree/main/Workshop%20-%20Git%20e%20Github)
  
- [Aula 01](https://github.com/lvgalvao/data-engineering-roadmap/tree/main/Bootcamp%20-%20Python%20para%20dados/aula01)

- [Aula 02](https://github.com/lvgalvao/data-engineering-roadmap/tree/main/Bootcamp%20-%20Python%20para%20dados/aula02)

- [Aula 03](https://github.com/lvgalvao/data-engineering-roadmap/tree/main/Bootcamp%20-%20Python%20para%20dados/aula03)

- [Aula 04](https://github.com/lvgalvao/data-engineering-roadmap/tree/main/Bootcamp%20-%20Python%20para%20dados/aula04)

- [Aula 05](https://github.com/lvgalvao/data-engineering-roadmap/tree/main/Bootcamp%20-%20Python%20para%20dados/aula05)

## 1. Versionamento

Segundo próprio [site do git](https://git-scm.com/), o git é um sistema de controle de versão distribuído e de código aberto que pode ser utilizado desde pequenos até grandes projetos.

__Curiosidade__: o Criador do git foi Linus Torvalds- sim o mesmo criador do Linux- e seu objetivo foi justamente melhorar a forma com que a equipe que desenvolvia o linux gerenciava seu desenvolvimento. O Repositório contendo todo desenvolvimento do linux pode ser encontrado [aqui](https://github.com/torvalds/linux)

## 1.1.Controle de versões sem git

Sem uso de git, o controle é feito em arquivos soltos com compartilhamento entre os membros via email e não há nenhuma forma de gerenciar qual versão está em produção.

!["cotrole de versão](./imagens/Semgit.svg "Versionamento sem git") < sub > Figura 1 — Controle de versões sem git .</sub>

## 1.2 Controle de Versões com git

Já com uso de git, a cada commit, é salvo um snapshot de cada arquivo de seu projeto, de modo que é possível rastrear cada versão, seu autor e as modificações realizadas.  

!["cotrole de versão](./imagens/Com_git.jpg "Versionamento Com git") < sub > Figura 2 — Controle de versões com git .</sub>

## 1.3 Git Vs Github

O Git é um programa de código aberto com funcionamento local. Já o Github é um serviço da microsoft que permite o controle de versões em nuvem, onde são implementados as funcionalidades do git além de outras.

## 1.4 Git/github e seus principais comandos

- [Instalar git](https://git-scm.com/)

!["cotrole de versão](./imagens/Integracao_gitgithub.png "Versionamento Com git") < sub > Figura 3 — Principais Comandos-Créditos: [Alison Pezzott](https://www.youtube.com/@alisonpezzott) .</sub>

- 1 Passo: Configurar seu usuário:

```
git config --global user.name "Seu Nome"  
git config --global user.email "seu.email@exemplo.com"
```

Para Verificar se configurou certo:
```
git config --global --list
```
este comando retornará seu usuário e email
