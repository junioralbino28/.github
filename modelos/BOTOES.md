# Botões de retorno dentro do app

Todo projeto com interface (app, site, editor) ganha, nas configurações ou no "Sobre", três botões que abrem o navegador:

| Botão | Abre |
|---|---|
| Dar uma estrela | `https://github.com/{{REPO}}` |
| Relatar um erro | `https://github.com/{{REPO}}/issues/new?template=erro.yml&versao=<versão>&sistema=<sistema>` |
| Mandar sugestão | `https://github.com/{{REPO}}/issues/new?template=sugestao.yml&versao=<versão>` |

- Os nomes depois de `?` são os `id` dos campos do formulário: o GitHub abre o formulário com esses campos já preenchidos.
- Preencha só o que é seguro: versão do app e sistema (ex.: `Windows 11`, `macOS 14.5`). **Nunca** nome de aparelho, de microfone ou de usuário: nome de fone Bluetooth costuma levar o nome do dono ("Fone de Fulano").
- Codifique os valores para URL (espaço vira `%20`).
- Para enviar, a pessoa precisa entrar na conta do GitHub. Sem conta, o GitHub pede para criar uma.
