# 📍 Sistema de Vigilância Comunitária

Plataforma colaborativa para mapeamento de crimes urbanos com base em denúncias públicas. O sistema visa aumentar a segurança por meio da informação, permitindo que cidadãos visualizem e contribuam com dados sobre a criminalidade em tempo real e de forma histórica.

---

## ❗ Declaração do Problema

As populações urbanas frequentemente enfrentam a insegurança causada pela ausência de informações públicas claras e atualizadas sobre a criminalidade em seus bairros. Denúncias são registradas de forma isolada e descentralizada, o que dificulta a visualização de padrões e o planejamento preventivo por parte da comunidade.

---

## ✅ Declaração da Solução

O sistema propõe uma plataforma interativa de vigilância comunitária onde qualquer pessoa pode registrar denúncias anônimas de crimes, visualizá-las em um mapa em tempo real e acompanhar estatísticas por bairro e período. O mapa destaca regiões com alta incidência criminal, auxiliando moradores, pesquisadores e autoridades na tomada de decisões baseadas em dados.

---

## 🎯 Objetivos do Sistema

- Reunir e exibir denúncias de crimes feitas pela comunidade.
- Exibir as regiões mais perigosas em um mapa com atualização constante.
- Disponibilizar estatísticas filtráveis por data, tipo de crime e localização.
- Permitir o uso da plataforma sem necessidade de cadastro.
- Promover maior consciência e ação preventiva sobre segurança urbana.

---

## 🧠 Público-Alvo

- Moradores de áreas urbanas
- Estudantes, pesquisadores e ONGs que estudam segurança pública
- Gestores públicos e conselhos de bairro
- Qualquer cidadão preocupado com a segurança da sua região

---

## ⚙️ Requisitos Funcionais (Histórias de Usuário)

> Formato: **Como [tipo de usuário], eu quero [objetivo] para que [benefício].**

---

### 1. Cadastro e Acesso

**Como** cidadão preocupado com a segurança,  
**quero** poder criar uma conta ou usar o sistema anonimamente,  
**para que** eu possa fazer denúncias com mais liberdade e acompanhar minhas contribuições.

---

### 2. Envio de Denúncia de Crime

**Como** usuário da plataforma,  
**quero** registrar uma denúncia com o tipo de crime, local, data e descrição,  
**para que** outros usuários e autoridades saibam do ocorrido na minha região.

---

### 3. Geolocalização de Ocorrências

**Como** denunciante,  
**quero** marcar o local do crime no mapa (manualmente ou via localização automática),  
**para que** a denúncia seja precisa e útil na análise geográfica.

---

### 4. Visualização de Mapa com Ocorrências

**Como** usuário da plataforma,  
**quero** visualizar um mapa interativo com os locais das denúncias,  
**para que** eu saiba quais áreas são mais perigosas.

---

### 5. Destaque de Áreas com Alta Criminalidade (Mapa de Calor)

**Como** usuário do mapa,  
**quero** ver as regiões com maior número de denúncias destacadas em vermelho,  
**para que** eu possa evitar essas áreas e entender melhor o nível de risco local.

---

### 6. Atualização em Tempo Real

**Como** usuário ativo do sistema,  
**quero** que as denúncias apareçam no mapa assim que forem registradas,  
**para que** eu tenha acesso a informações atualizadas sobre a criminalidade.

---

### 7. Filtros de Visualização

**Como** usuário interessado em segurança,  
**quero** filtrar os crimes por tipo, data ou bairro,  
**para que** eu possa analisar as informações que mais me interessam.

---

### 8. Estatísticas por Período

**Como** cidadão ou analista,  
**quero** visualizar estatísticas de crimes por semana, mês ou ano,  
**para que** eu possa identificar padrões e tendências de criminalidade.

---

### 9. Estatísticas Consolidadas

**Como** pesquisador ou gestor público,  
**quero** acessar dados consolidados de todos os crimes registrados,  
**para que** eu possa tomar decisões baseadas em dados históricos completos.

---

### 10. Moderação de Denúncias

**Como** administrador da plataforma,  
**quero** revisar e moderar denúncias suspeitas ou abusivas,  
**para que** o sistema mantenha a confiabilidade e evite mau uso.

---

### 11. Acesso a Painel Administrativo

**Como** operador do sistema,  
**quero** acessar um painel com denúncias, estatísticas e ferramentas de moderação,  
**para que** eu possa gerenciar o conteúdo e monitorar o sistema de forma eficiente.

---

### 12. Interface Responsiva

**Como** usuário de smartphone,  
**quero** acessar o sistema com uma interface adaptada ao meu dispositivo,  
**para que** eu possa utilizar todos os recursos com facilidade onde estiver.

---

## 🚫 Requisitos Não Funcionais

- A plataforma deve ser responsiva e funcionar em dispositivos móveis e desktops.
- As denúncias devem ser armazenadas em banco de dados seguro com backup automático.
- O sistema deve garantir o anonimato do usuário, mesmo sem autenticação.
- O tempo de resposta do sistema deve ser inferior a 2 segundos para qualquer consulta.
- A interface deve ser acessível (seguir critérios WCAG para contraste, navegação etc.).
- A infraestrutura deve suportar atualizações em tempo real (websockets ou polling).
- O sistema deve ser escalável para suportar grande volume de denúncias e acessos simultâneos.

---

## 📊 Tecnologias Sugeridas (exemplo)

- **Frontend:** React ou Vue.js com Leaflet.js (para mapas)
- **Backend:** Node.js + Express / NestJS
- **Banco de Dados:** PostgreSQL ou MongoDB
- **Hospedagem:** Vercel / Render / Railway
- **Segurança:** Autenticação JWT + anonimato opcional

---

## 📌 Roadmap (exemplo)

1. Criação de MVP com mapa e denúncias básicas
2. Implementação de estatísticas filtráveis
3. Integração com painel de moderação
4. Suporte a notificações e atualizações em tempo real
5. Deploy e divulgação comunitária

---

## 📬 Contribuições

Contribuições são bem-vindas!  
Para contribuir:

1. Faça um fork do repositório
2. Crie uma branch com sua feature
3. Faça commits descritivos
4. Envie um Pull Request com sua proposta

---

## 📎 Licença

Este projeto está licenciado sob a [MIT License](./LICENSE).

---


