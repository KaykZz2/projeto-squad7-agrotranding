# 🌾 AgroTrading

Plataforma digital de leilões e negociações diretas entre **produtores rurais** e **compradores corporativos** (mercados, hortifrutis e restaurantes), focada no comércio eficiente, transparente e competitivo de hortifrútis (frutas, legumes e verduras).

---

## 📌 Sobre o Projeto

A **AgroTrading** surge para resolver o gargalo de comercialização de produtos agrícolas. De um lado, produtores rurais enfrentam dificuldades para escoar safras antes de sua deterioração; de outro, estabelecimentos comerciais precisam repor estoque com agilidade, preços competitivos e transparência de entrega.

Através de um **modelo de leilão com ofertas dinâmicas**, a plataforma possibilita que compradores analisem e comparem em um só ambiente:
`Produtor` ➔ `Produto` ➔ `Quantidade (kg)` ➔ `Qualidade (Tipo A/B/C)` ➔ `Preço Inicial` ➔ `Prazo/Condição`

### 🎯 Objetivos de Desenvolvimento Sustentável (ODS)
- **ODS 2 - Fome Zero e Agricultura Sustentável:** Aproximação comercial e valorização de produtores rurais.
- **ODS 8 - Trabalho Decente e Crescimento Econômico:** Geração de renda e expansão de mercado para pequenos e médios produtores.
- **ODS 12 - Consumo e Produção Responsáveis:** Otimização de oferta e demanda, reduzindo o desperdício de alimentos.

---

## 👥 Squad de Desenvolvimento

| Nome | RA | Papel / Função |
| :--- | :--- | :--- |
| **Thais Novaes Rodrigues de Lima** | `45930431` | Product Owner (PO) |
| **Raiana Vilardo Martin da Silva** | `45055611` | Scrum Master |
| **Gabriel Silva Diniz** | `45618496` | Engenheiro de Software |
| **Kayk Ferreira Cândido** | `44883421` | Engenheiro de Software |
| **Geovanna Cristina Santos Costa** | `44878745` | Engenheira de Software |
| **Augusto Lima** | `45633355` | Engenheiro de Software |

---

## 🚀 Funcionalidades da Plataforma (Escopo do Projeto)

### 👥 1. Módulo de Usuários
- Cadastro e Autenticação via **JWT**.
- Perfis distintos para **Produtor Rural** (CPF/CNPJ, Cadastro Produtor) e **Comprador** (CNPJ corporativo).

### 📦 2. Módulo de Lotes e Leilão
- Produtor cadastra lotes com: Produto, Quantidade (kg), Qualidade (Tipo A/B/C), Preço Inicial, Fotos (até 3), Validade e Modalidade (Entrega/Retirada).
- Lances em tempo real com valor crescente e histórico visível.
- Aceite do lance pelo produtor transforma o lote em **Pedido Arrematado** (#101).

### 🔍 3. Módulo de Busca e Comparativo
- Listagem de lotes ativos com filtros por produto, cidade, qualidade e tipo de entrega.
- Ordenação por menor preço e prazo de entrega.

### 🚚 4. Acompanhamento de Pedido (`Meus Pedidos`)
Status atualizável manualmente pelo produtor:
- **Para Retirada:** *Pedido Confirmado ➔ Em Separação ➔ Pronto para Retirada ➔ Retirado/Concluído*
- **Para Entrega:** *Pedido Confirmado ➔ Em Separação ➔ Saiu para Entrega ➔ Entregue/Concluído*

### ⭐ 5. Avaliação Mútua
- Liberada somente após a conclusão (*Entregue* ou *Retirado*).
- Nota (1 a 5 estrelas) + comentários. Exibição da média no perfil de produtores e compradores.

### 📊 6. Dashboard
- Métricas de lotes ativos, pedidos em andamento e média de reputação dos usuários.

---

## 📊 Indicadores de Desempenho (KPIs)

1. **Taxa de Conclusão de Pedidos:**
   $$\text{Taxa de Conclusão} = \left(\frac{\text{Pedidos Concluídos}}{\text{Pedidos Realizados}}\right) \times 100$$
   - *Meta Inicial:* **≥ 70%**

2. **Tempo Médio para Encontrar Oferta:**
   $$\text{Tempo Médio} = \frac{\sum \text{Tempo de Busca}}{\text{Total de Buscas}}$$
   - *Meta Inicial:* **≤ 3 minutos**

---

## 📅 Planejamento de Entregas (4 Etapas)

- [x] **Etapa 1:** Planejamento, Visão, Personas e Levantamento de Requisitos.
- [ ] **Etapa 2:** Design UX/UI, Wireframes e Protótipo Navegável.
- [ ] **Etapa 3:** Modelagem do Banco de Dados, Backend, Frontend e Lógica de Leilão.
- [ ] **Etapa 4:** Testes Funcionais, Usabilidade, Correção de Bugs e Apresentação.

📌 **Acompanhamento do Projeto (Notion Board):** [Quadro do Projeto AgroTrading](https://app.notion.com/p/3d13e1911e61800f92e2e0bb8dbe9fd8?v=8d2921a73d4d406897556561eb8b095b)

---

## 🔒 Conformidade LGPD & Segurança

A plataforma opera estritamente em conformidade com a **Lei Geral de Proteção de Dados (Lei nº 13.709/2018)**:
- **Bases Legais:** Execução de contrato (Art. 7º, V) e Consentimento expresso (Art. 7º, I).
- **Segurança:** Armazenamento seguro de senhas via hash criptográfico não reversível, tráfego seguro via protocolo HTTPS e controle rigoroso de acesso à base de dados.
- **Direitos do Titular:** Garantia de solicitação de visualização, retificação ou exclusão de cadastro a qualquer momento (Art. 18).

---

## 📄 Licença

Este projeto é desenvolvido para fins acadêmicos. Todos os direitos reservados à equipe de desenvolvimento AgroTrading.
