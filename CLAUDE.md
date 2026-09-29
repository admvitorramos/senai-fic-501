# CLAUDE.md — senai-fic-501 (Material de Aula)

Diretrizes para qualquer agente (Claude Code ou outro) trabalhando neste repositório.

## Sobre o projeto
Repositório público de material didático da turma SENAI FIC 501. Contém conteúdo de
aula, exercícios e enunciados para os alunos. **Não deve conter gabaritos** —
gabaritos ficam em `senai-fic-501-gabaritos` (privado).

## Fluxo de submissão dos alunos: Fork & Pull Request

1. **Fork**: cada aluno faz um fork deste repositório para sua própria conta GitHub.
2. **Clone**: clona o fork localmente (`git clone https://github.com/<seu-usuario>/senai-fic-501`).
3. **Branch**: cria uma branch com o padrão `entrega/<numero-aula>-<nome-aluno>`
   (ex.: `entrega/03-joao-silva`).
4. **Trabalho**: resolve o exercício dentro da pasta indicada pelo instrutor
   (ex.: `entregas/aula-03/joao-silva/`), sem alterar arquivos de outros alunos ou do
   material base.
5. **Commit**: mensagens de commit claras (`feat: resolve exercicio 3 da aula 03`).
6. **Push**: envia a branch para o próprio fork (`git push origin entrega/03-joao-silva`).
7. **Pull Request**: abre um PR do fork para a branch `main` deste repositório,
   descrevendo o que foi feito e referenciando o número da aula.
8. **Revisão**: o instrutor revisa o PR, pode pedir ajustes via comentários; o aluno
   ajusta com novos commits na mesma branch.
9. **Nunca commitar diretamente na `main`** — a branch `main` é protegida e exige PR.

## Regras adicionais
- Não subir soluções completas nem gabaritos neste repositório.
- Manter a estrutura de pastas por aula (`aula-01/`, `aula-02/`, ...) consistente.
- Conteúdo deve ser didático, com comentários explicativos quando relevante para os alunos.
