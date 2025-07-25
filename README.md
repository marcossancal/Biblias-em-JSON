# 📖 Repositório de Versões da Bíblia — JSON e MySQL

Este repositório contém diversas versões da **Bíblia Sagrada** formatadas em **JSON**
O objetivo é fornecer um recurso acessível, estruturado e de código aberto para desenvolvedores, ministérios e projetos cristãos que desejam usar a Palavra de Deus em seus sistemas e aplicações.

> _“Portanto, vão e façam discípulos de todas as nações...”_  
> — Mateus 28:19

## ✝️ Propósito

Este projeto foi criado com um forte desejo de cumprir a **Grande Comissão**, facilitando a distribuição das Escrituras por meios digitais.  
Com ele, você pode:

- Integrar versões da Bíblia em sites, aplicativos e APIs
- Fazer estudos bíblicos programaticamente
- Alimentar bancos de dados com textos bíblicos organizados
- Contribuir para projetos missionários e ferramentas cristãs open source
---

## 📦 Estrutura do Repositório

📁 json/
└── biblia_ave_maria.json
└── biblia_nova_versao_internacional.json
└── ... outras versões

📁 sql/
└── biblia_ave_maria.sql
└── ... arquivos de importação MySQL

## 🛠 Como Usar

### 📥 1. Importar para o MySQL

1. Crie a tabela no seu banco:

```sql
CREATE TABLE biblia (
    id INT PRIMARY KEY,
    versao VARCHAR(50),
    livro VARCHAR(10),
    capitulo INT,
    versiculo TEXT
);
```

🚀 Contribuições
Sinta-se à vontade para:

Adicionar novas versões da Bíblia

Traduzir o conteúdo
Abrir issues e PRs com sugestões ou correções

🙌 Que este projeto seja uma bênção
Se este repositório for útil para você, considere compartilhá-lo com outros ministérios e desenvolvedores cristãos.
Toda glória seja dada a Deus!

“A fé vem pelo ouvir, e o ouvir pela palavra de Deus.”
— Romanos 10:17