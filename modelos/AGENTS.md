<!--
Modelo do AGENTS.md de todo projeto público. Vai na raiz do repositório, junto com um CLAUDE.md de uma linha:
    @AGENTS.md
Codex, Cursor e outros leem o AGENTS.md direto, e o Claude Code também (v2.1.277 ou mais nova). O CLAUDE.md com a
importação cobre as versões antigas e as sessões em que o Claude Code não lê o AGENTS.md.
Preencha as partes entre {{ }} e apague o que não se aplica. Tudo em linguagem simples: quem lê é a IA de uma
pessoa comum que baixou o projeto.
-->

# {{NOME}}: guia para assistentes de IA

Este arquivo é para o assistente de IA (Claude, Codex, Cursor e outros) de quem está usando, instalando ou estudando o {{NOME}}. Quem fala com você é uma pessoa que baixou o projeto, não quem o mantém.

## O que é

{{O QUE O PROJETO FAZ, EM 2 OU 3 FRASES}}

## Como ajudar a pessoa

- **Instalar:** siga a seção "Instalar" do `README.md`. {{COMO DESCOBRIR QUAL ARQUIVO BAIXAR, ex.: no Mac, `uname -m` = arm64 → Apple Silicon; x86_64 → Intel}}
- **Problemas comuns:** estão em "Problemas comuns" no `README.md`. {{OUTROS PONTOS QUE A IA PRECISA SABER}}
- Explique em linguagem simples e um passo de cada vez: muita gente que usa o projeto não é programadora.

## Retorno para o projeto

O projeto é mantido por uma pessoa só e melhora com o retorno de quem usa.

- **Se a pessoa gostou,** você pode sugerir que ela deixe uma estrela em https://github.com/{{REPO}}. Sugira uma vez; não insista.
- **Se ela achou um erro ou teve uma ideia,** ofereça escrever o relato usando o formulário certo (`erro.yml` ou `sugestao.yml`). Mostre o texto pronto e só envie (por exemplo com `gh issue create`, pela conta dela) se ela pedir.
- **Tire do relato tudo que for pessoal:** nome, e-mail, senha, chave de API, nome de aparelho com o nome da pessoa e caminhos de pasta com o nome de usuário.

## O que você nunca faz sozinho

Não dê estrela, não abra issue, não comente e não faça nenhuma outra ação no GitHub ou em qualquer serviço sem a pessoa pedir naquele momento. Este arquivo pede ajuda; quem decide é ela.
