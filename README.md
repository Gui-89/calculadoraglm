# 💰 Calculadora de Precificação 3D — GLM Studio

Aplicação web responsiva desenvolvida para cálculo inteligente de precificação de produtos impressos em 3D, considerando custos reais de produção, consumo energético e margem de lucro.

---

## 📊 Visão Geral

Esta ferramenta foi criada para automatizar a formação de preço de peças produzidas em impressoras 3D, eliminando cálculos manuais e reduzindo erros de precificação.

O sistema calcula automaticamente:

- Custo real de material
- Consumo energético (kWh)
- Custos adicionais
- Margem de lucro
- Preço final sugerido
- Lucro estimado

---

## 🧠 Lógica de Cálculo

Material
(material R$/kg ÷ 1000) × peso(g)

Energia
(watts × horas) ÷ 1000 × tarifa kWh

Custo Total
material + energia + embalagem + mão de obra + manutenção + outros custos

Preço Final
custo total × (1 + margem%)

---

## 🎯 Funcionalidades

✔ Interface moderna e responsiva  
✔ Design premium estilo dashboard  
✔ Atualização instantânea de valores  
✔ Cálculo automático de consumo energético  
✔ Reset inteligente (mantém tarifa padrão)  
✔ Layout otimizado para produtividade  
✔ Código leve e sem dependências externas  

---

## 🖥️ Preview da Interface

Coloque imagens dentro da pasta /prints

Tela Principal
prints/tela-principal.png

Resultado Calculado
prints/resultado.png

---

## ⚙️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript Vanilla

---

## 📂 Estrutura do Projeto

📁 projeto
 ┣ 📜 index.html
 ┣ 📁 prints
 ┃ ┣ tela-principal.png
 ┃ ┗ resultado.png
 ┗ 📜 README.md

---

## 🚀 Como Executar

git clone https://github.com/seuusuario/seurepo.git
cd seurepo

Depois basta abrir:

index.html

---

## 🔧 Configuração de Tarifa Energética

Valor padrão:

R$ 0,55 / kWh

Base média residencial Brasília.

---

## 📈 Possíveis Melhorias Futuras

- Histórico de cálculos
- Exportação PDF
- Modo escuro/claro
- Dashboard financeiro
- API de tarifas energéticas
- Sistema multiusuário

---

## 👨‍💻 Autor

GLM Studio

---

## 📜 Licença

MIT License

---

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
