# 📊 Tabelas em HTML

![Badge HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge Estudos](https://img.shields.io/badge/estudos-Tabelas%20HTML-blue)
![Badge Organização](https://img.shields.io/badge/dados-Tabelas%20e%20Estruturas-green)

## 📚 Sobre o Projeto
Este arquivo HTML faz parte dos meus estudos sobre **tabelas em HTML**. Aprendi a criar tabelas estruturadas, usar cabeçalhos, mesclar células (colspan e rowspan) e organizar o conteúdo com as tags semânticas `<thead>`, `<tbody>` e `<tfoot>`.

## 📁 Arquivo
| Arquivo | Descrição |
|---------|-----------|
| `tabelas.html` | Demonstra a criação de tabelas HTML com diferentes níveis de complexidade |
| `README.md` | Resumo do arquivo tabelas.html e explicação de todas as tags utilizadas |

## 🎯 O que aprendi

### Tags Fundamentais para Tabelas:

| Tag | Significado | Função |
|-----|-------------|--------|
| `<table>` | Tabela | Container principal da tabela |
| `<tr>` | Linha da tabela | Define uma linha |
| `<th>` | Cabeçalho | Célula de cabeçalho (negrito e centralizado) |
| `<td>` | Dado da tabela | Célula com dados |
| `<caption>` | Legenda | Título/legenda da tabela |

### Tags Semânticas para Tabelas:

| Tag | Significado | Função |
|-----|-------------|--------|
| `<thead>` | Cabeçalho da tabela | Agrupa o conteúdo do cabeçalho |
| `<tbody>` | Corpo da tabela | Agrupa o conteúdo principal |
| `<tfoot>` | Rodapé da tabela | Agrupa o conteúdo do rodapé |

### Atributos Importantes:

| Atributo | Função | Exemplo |
|----------|--------|---------|
| `border` | Define a borda da tabela | `border="1"` |
| `width` | Largura da tabela | `width="50%"` |
| `colspan` | Mescla colunas | `colspan="4"` |
| `rowspan` | Mescla linhas | `rowspan="2"` |

## 🖥️ Exemplos do Código

### Tabela Simples
```html
<table border="1" width="50%">
    <caption>Legenda da tabela</caption>
    <tr>
        <th>Cabeçalho 1</th>
        <th>Cabeçalho 2</th>
        <th>Cabeçalho 3</th>
    </tr>
    <tr>
        <td>Célula 1</td>
        <td>Célula 2</td>
        <td>Célula 3</td>
    </tr>
</table>
```

### 🏗️ Estrutura Semântica da Tabela:
```
┌─────────────────────────────────────┐
│             <thead>                  │
│  ┌─────────────────────────────────┐ │
│  │  th (colspan=4) - Título        │ │
│  └─────────────────────────────────┘ │
├───────────────────────────────────────┤
│             <tbody>                    │
│  ┌─────┬───────┬───────┬───────┐     │
│  │ td  │  td   │  td   │  td   │     │
│  │(rowspan=2)                       │
│  ├─────┼───────┼───────┼───────┤     │
│  │     │  td   │  td   │  td   │     │
│  └─────┴───────┴───────┴───────┘     │
├───────────────────────────────────────┤
│             <tfoot>                    │
│  ┌─────────────────────────────────┐ │
│  │  td (texto do rodapé)           │ │
│  └─────────────────────────────────┘ │
└─────────────────────────────────────┘

```
## 👨‍💻 Autor
**Richard Teixeira**
```
Estudante de Sistemas de Informação apaixonado por tecnologia.
📚 Atualmente: HTML, CSS e Python
🎯 Meta: Primeira oportunidade como desenvolvedor
```
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TSRichard)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tsrichard/)
