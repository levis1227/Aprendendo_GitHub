# Como Adicionar uma Pasta no GitHub

Este guia explica de forma simples como criar e organizar pastas dentro do seu repositório, seja pela interface web ou pelo terminal.

---

## 1. Pelo Navegador (GitHub Web)

O GitHub não permite a existência de pastas vazias. Para criar uma pasta, você deve criar um arquivo dentro dela simultaneamente.

1.  Aceda ao seu repositório no GitHub.
2.  Clique no botão **Add file** e selecione **Create new file**.
3.  No campo do nome do arquivo, digite o nome da pasta que deseja criar seguido de uma barra lateral `/`.
    * *Exemplo:* `documentacao/`
4.  Note que o GitHub criará uma "caixa" indicando o diretório. Agora, digite o nome do arquivo (ex: `README.md`).
5.  Adicione algum conteúdo ao arquivo.
6.  Clique em **Commit changes...** para salvar a pasta e o arquivo.


## Exemplo visual:

<img width="928" height="373" alt="image" src="https://github.com/user-attachments/assets/d4e3f471-3f02-49c5-8b47-347329156c54" />

<img width="1447" height="673" alt="image" src="https://github.com/user-attachments/assets/7487e758-5b16-449c-9098-7df3fb80df97" />

<img width="1280" height="316" alt="image" src="https://github.com/user-attachments/assets/02590373-fc5f-4e81-b24b-665ab323e9ef" />

---

## 2. Pelo Terminal (Git CLI)

Se estiver a trabalhar no seu computador e quiser enviar a pasta para o GitHub:

1.  Abra o terminal na pasta do projeto.
2.  Crie o novo diretório:
    ```bash
    mkdir nome-da-minha-pasta
    ```
3.  Crie um arquivo dentro (o Git não rastreia pastas vazias):
    ```bash
    touch nome-da-minha-pasta/.gitkeep
    ```
4.  Suba as alterações:
    ```bash
    git add .
    git commit -m "Adicionando nova pasta"
    git push origin main
    ```

