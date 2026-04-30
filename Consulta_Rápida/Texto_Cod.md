# Orientação

Para usar direito esse guia, veja o que você quer fazer e depois procure esse trecho no código para saber como replicar.

## 1. Estilização de Texto

O Markdown permite destacar textos de diversas formas:

* **Texto normal**
* **Negrito**: `**negrito**` ou `__negrito__`
* *Itálico*: `*itálico*` ou `_itálico_`
* ***Negrito + Itálico***: `__*texto*__` ou `**_texto_**`
* ~~Riscado~~: `~~texto~~`

---

## 2. Cabeçalhos (Títulos)

# Título 1
## Título 2
### Título 3

---

## 3. Listas

### Lista Numerada
1. Teste
2. Teste2
3. Teste3

### Lista Demarcada (Bullets)
* Teste
* Teste
    * Sub-item (indentado)
* Teste
- Teste
- Teste

### Lista de Tarefas (Task List)
- [x] Criar a página principal
- [x] Criar a página da loja
- [ ] Finalizar a reunião com o cliente
- [ ] Receber o pagamento

---

## 4. Links e Imagens

### Links
[Acesse esse vídeo](https://youtube.com/shorts/Pg8Md_7oV-M?si=wKP2FFNIRdOEesA8)

### Imagens
Recomendado até 500 pixels. Exemplo de inserção via HTML para controle de tamanho:

<img width="522" height="268" alt="maquina (1)" src="https://github.com/user-attachments/assets/cee91036-36f0-4cbc-8db1-cf503caa70cb" />

---

## 5. Tabelas

| Num | Nome | Nota |
| :--- | :--- | :--- |
| 1 | Gustavo | 8,5 |
| 2 | José | 10,0 |
| 3 | Maria | 9,0 |

---

## 6. Blocos de Código (Crase)

### Inline Code
Útil para identificar comandos no meio do texto, como o comando `document.getElementById()`.

### Bloco de Código (Python)
```python
num = int(input('Digite um valor:'))

if num % 2 == 0:

   print(f'O valor {num} é PAR')

else:

   print(f'O valor {num} é ÍMPAR')
```
