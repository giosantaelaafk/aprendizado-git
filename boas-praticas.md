# 🍄 Boas práticas de Git e GitHub

Organizar o histórico de um projeto é essencial para facilitar a manutenção do código, acompanhar alterações e colaborar com outras pessoas. 🌱

## 1. Escreva mensagens de commit claras

Use mensagens curtas e descritivas que expliquem o que foi alterado.

**Exemplo:** `docs: adiciona README do projeto`

Isso facilita a identificação das mudanças no histórico.

## 2. Crie branches para novas funcionalidades

Desenvolva novas funcionalidades em branches separadas da branch principal (`main`).

**Exemplo:** `feature/boas-praticas`

Assim, as alterações podem ser desenvolvidas e revisadas antes de serem integradas à versão principal.

## 3. Revise as alterações antes de fazer o commit

Utilize `git status` para conferir o estado dos arquivos e `git diff` para visualizar as alterações realizadas antes de registrá-las.

Isso ajuda a evitar que arquivos ou mudanças indesejadas sejam incluídos no commit.

## 4. Utilize Pull Requests para integrar mudanças

Abra um Pull Request para propor a integração de uma branch à `main`.

Revise os arquivos modificados, verifique se a descrição está clara e solicite aprovação antes de mesclar as alterações, conforme o fluxo de trabalho do projeto.

## 5. Não compartilhe informações sensíveis

Nunca envie senhas, tokens de acesso, chaves privadas ou outras credenciais para um repositório público.

Utilize mecanismos seguros para armazenar informações confidenciais.

