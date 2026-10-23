# Prática de Git e GitHub — EBAC

Exercício introdutório de versionamento que propõe clonar um repositório, editar o arquivo `dados.txt`, registrar a alteração em um commit e publicar o trabalho no GitHub.

## Objetivos
- Praticar clone, edição de arquivos e commits.
- Entender o fluxo básico de trabalho com Git.
- Publicar alterações em um repositório remoto.

## Tecnologias
- Git
- GitHub
- Arquivo texto (`dados.txt`)

## Pré-requisitos
- Git instalado e configurado.
- Conta GitHub e acesso ao repositório.

## Como executar
```bash
git clone https://github.com/Nickgdm/aula-git-ebac.git
cd aula-git-ebac
```
Edite `dados.txt`, depois registre a alteração:
```bash
git add dados.txt
git commit -m "Modificando o arquivo de dados"
git push
```
O comando `git push` requer que o remoto e as permissões estejam configurados corretamente.

## Estrutura do projeto
```text
aula-git-ebac/
├── dados.txt
└── README.md
```

## Desafios práticos
Realizar o fluxo básico de obtenção do projeto, edição, preparação da alteração, criação de commit e envio para o GitHub.

## Boas práticas adotadas
- Uso de commits com mensagem relacionada à alteração.
- Versionamento do arquivo editado.
- Separação entre o arquivo de atividade e suas instruções.

## 📚 Aprendizados
A atividade permitiu praticar o fluxo básico de versionamento com Git e GitHub: clonar um repositório, editar arquivos, preparar alterações, criar commits e publicar as mudanças em um repositório remoto.

## Considerações finais
Este é um exercício introdutório de controle de versão. O arquivo `dados.txt` pode conter informações de exemplo; evite publicar dados pessoais ou sensíveis.

---

## 🎓 Formação
Atividade desenvolvida durante a formação profissionalizante em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**.