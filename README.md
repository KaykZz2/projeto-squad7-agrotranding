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

## ⚙️ Fora do Escopo Atual

Para manter a viabilidade e entrega contínua, os seguintes itens não fazem parte desta fase do projeto:
- 🚫 Rastreamento em tempo real via GPS.
- 🚫 Gateway de pagamento online integrado (pagamento e frete combinados via WhatsApp após arremate).
- 🚫 Aplicativo móvel nativo / Notificações Push.
- 🚫 Chat em tempo real via WebSocket.
| **Geovanna Cristina Santos Costa** | `44878745` | Engenheira de Software |
| **Augusto Lima** | `45633355` | Engenheiro de Software |
