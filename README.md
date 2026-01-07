# 🚗 Consulta de Origem de Placa - Brasil

Uma aplicação web simples e elegante para consultar o estado de origem de placas de veículos brasileiros através das três primeiras letras de uma placa.

## 📋 Sobre o Projeto

Este sistema permite identificar rapidamente em qual estado brasileiro um veículo foi emplacado originalmente, baseando-se nas três primeiras letras da placa. A consulta é instantânea e funciona tanto para o padrão antigo quanto para as placas do padrão Mercosul.

## ✨ Funcionalidades

- **Consulta Rápida**: Digite apenas as 3 primeiras letras da placa
- **Interface Intuitiva**: Design limpo e responsivo com paleta "Papel & Vinho"
- **Validação Automática**: Aceita letras maiúsculas e minúsculas
- **Atalho de Teclado**: Pressione Enter para consultar
- **Base de Dados Completa**: Inclui todos os estados brasileiros

## 🎨 Design

O projeto utiliza uma identidade visual clássica e atemporal com a paleta de cores "Papel & Vinho":

- **Creme** (#F5EFE6): Fundo do container
- **Papel** (#EADCCA): Fundo da página
- **Café** (#2E1A16): Textos principais
- **Vinho Bordô** (#8A1C1C): Botões e destaques
- **Bordas suaves** (#D1C0B0): Delimitações discretas

## 🚀 Como Usar

1. Acesse a aplicação no navegador
2. Digite as **3 primeiras letras** da placa no campo de entrada
3. Clique em **"Consultar"** ou pressione **Enter**
4. O estado de origem será exibido instantaneamente

**Exemplo**: 
- Digite `ABC` → Resultado: Estado do Paraná
- Digite `JKL` → Resultado: Estado de São Paulo

## 🛠️ Tecnologias

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna e responsiva
- **JavaScript (Vanilla)**: Lógica de consulta
- **JSON**: Base de dados de placas

## 📁 Estrutura do Projeto

```
consultaplacas/
├── index.html      # Página principal com toda a lógica
├── placas.json     # Base de dados com faixas de placas por estado
├── vercel.json     # Configuração de deploy
└── README.md       # Este arquivo
```

## 📊 Base de Dados

A aplicação utiliza um arquivo JSON (`placas.json`) contendo as faixas de letras atribuídas a cada estado brasileiro. O sistema compara as 3 primeiras letras da placa informada com essas faixas para determinar a origem.

## 🌐 Deploy

O projeto está configurado para deploy na Vercel através do arquivo `vercel.json`.

## 👨‍💻 Desenvolvedor

**Gustavo Ceolin**
- [LinkedIn](https://www.linkedin.com/in/gustavo-ceolin-21b36b217/)

## 📄 Licença

Projeto de código aberto para fins educacionais e de consulta pública.

---

💡 **Nota**: As informações são baseadas no sistema oficial de emplacamento brasileiro. A base de dados é atualizada com fontes da internet.
