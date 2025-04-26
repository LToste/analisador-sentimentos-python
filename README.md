# Analisador de Sentimentos em Comentários

Este projeto realiza uma análise simples de sentimentos (positivo, negativo ou neutro) a partir de comentários escritos em um arquivo CSV.

## 🛠️ Tecnologias usadas

- Python 3
- Pandas
- Google Colab

## 📂 Como usar

1. Faça upload do seu arquivo CSV no Google Colab.  
   - O arquivo deve conter uma coluna chamada `comentario`.
2. O script vai ler os comentários e analisar se são positivos, negativos ou neutros.
3. Um novo arquivo `comentarios_analisados.csv` será gerado automaticamente para download.

### 📄 Exemplo de entrada (`reviews.csv`):

| comentario |
|------------|
| Produto excelente! |
| Péssimo atendimento. |
| É razoável, nem bom nem ruim. |
| Maravilhoso, super recomendo! |

### 📄 Exemplo de saída (`comentarios_analisados.csv`):

| comentario                        | sentimento |
|-----------------------------------|------------|
| Produto excelente!                | Positivo   |
| Péssimo atendimento.              | Negativo   |
| É razoável, nem bom nem ruim.      | Neutro     |
| Maravilhoso, super recomendo!      | Positivo   |

## ✨ Autor

Projeto desenvolvido por [Lorena França](www.linkedin.com/in/lorena-franca-rocha)

---
