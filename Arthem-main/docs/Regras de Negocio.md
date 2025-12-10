# Regras de Negócio — Galeria de Arte Angolana

---

## 1. Regras sobre Artistas e Obras

### 1.1 Cadastro de Artistas
- Cada artista deve possuir um perfil com:
  - Nome
  - Biografia
  - Contactos
  - Categorias de atuação (ex.: pintura, escultura)

### 1.2 Propriedade das Obras
- Toda obra cadastrada deve estar vinculada a um artista válido.

### 1.3 Classificação das Obras
- Cada obra deve ser classificada obrigatoriamente em **uma** das categorias:
  - Pintura
  - Escultura
  - Fotografia

### 1.4 Informações Obrigatórias das Obras
- Uma obra só pode ser publicada se possuir:
  - Título
  - Descrição
  - Foto
  - Categoria
  - Dimensões
  - Estado de disponibilidade (à venda, vendida, não disponível)

### 1.5 Destaque de Obras
- O administrador pode marcar algumas obras como **"Em Destaque"** para maior visibilidade na página inicial.

---

## 2. Regras de Negócio da Venda Online

### 2.1 Disponibilidade de Venda
- Uma obra só pode ser listada como disponível para compra se o artista autorizar a venda.

### 2.2 Preço Definido
- Toda obra à venda deve ter preço definido pelo artista.

### 2.3 Venda Exclusiva
- Uma obra só pode ser reservada ou vendida para um cliente por vez.

### 2.4 Confirmação de Venda
- A venda só é concluída após confirmação do artista.

### 2.5 Método de Pagamento / Contacto
- A plataforma deve permitir que o comprador entre em contacto via canais fornecidos (ex.: e‑mail, WhatsApp) para completar o processo de pagamento.

---

## 3. Regras de Agenda Cultural

### 3.1 Registro de Eventos
- Todo evento deve conter:
  - Nome
  - Data
  - Local
  - Descrição
  - Imagem (opcional)

### 3.2 Ordenação por Data
- Eventos futuros devem aparecer antes dos eventos passados na listagem da agenda.

### 3.3 Validade das Informações
- Eventos não podem ser publicados com datas inválidas ou já decorridas (exceto como **"Eventos Passados"**).

---

## 4. Regras Administrativas

### 4.1 Gestão dos Papéis
- Apenas administradores podem cadastrar, editar ou remover:
  - Obras
  - Artistas
  - Eventos

### 4.2 Publicação Moderada
- Uma obra ou evento só aparece publicamente após aprovação do administrador.

---

## 5. Regras de Experiência do Visitante

### 5.1 Acesso Livre
- Visitantes podem visualizar obras e eventos sem necessidade de login.

### 5.2 Filtros e Pesquisa
- O visitante pode filtrar obras por:
  - Categoria
  - Faixa de preço

### 5.3 Transparência de Informação
- Todos os itens à venda devem exibir claramente:
  - Preço
  - Estado (Disponível, Reservada, Vendida)

---

## Observações Gerais
- Corrigir e padronizar termos durante a implementação (ex.: grafia, campos obrigatórios).
- Validar autorizações e confirmações de artistas antes de listar itens à venda.

---
