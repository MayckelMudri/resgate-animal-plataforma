#  Plataforma de Intermediação de Resgate Animal 

Este projeto propõe a criação de uma plataforma web social voltada ao resgate de animais perdidos ou abandonados dentro de condomínios, conectando de forma rápida e organizada administradoras de condomínios, ONGs de proteção animal e, futuramente, órgãos públicos.

A iniciativa nasce de um problema real e recorrente: animais que entram em condomínios, muitas vezes machucados, famintos ou em risco, sem que exista um fluxo eficiente de comunicação para o resgate adequado.

##  Contexto do Problema

Em condomínios residenciais e áreas urbanas, é comum a entrada de animais abandonados ou perdidos. Atualmente, não existe um canal centralizado, estruturado e rastreável que permita que administradoras, síndicos e ONGs se comuniquem de forma eficiente para viabilizar o resgate desses animais.

## Essa ausência de organização gera:

- Atraso no atendimento
- Falta de comunicação entre as partes
- Sobrecarga das ONGs
- Ocorrências sem solução

##  A Solução Proposta

### A Plataforma de Intermediação de Resgate Animal atua como um ponto central de registro e acompanhamento de ocorrências, permitindo que:

- Condomínios registrem ocorrências de animais encontrados
- ONGs credenciadas visualizem e aceitem resgates
- O andamento do resgate seja acompanhado em tempo real
- Dados sejam registrados para análise e políticas públicas

A plataforma **não executa o resgate**, mas **intermedia e organiza** o processo.

## Objetivo Principal

### Criar um sistema centralizado que permita:

- Registrar ocorrências de animais encontrados em condomínios
- Notificar automaticamente ONGs parceiras
- Acompanhar o status do resgate
- Gerar dados e relatórios que apoiem políticas públicas de proteção animal

##  Impacto Social
  
### Para os Animais  

- Redução do tempo de exposição ao risco
- Resgates mais rápidos e organizados
- Maior chance de recuperação e adoção

### Para Condomínios 

- Canal oficial e padronizado para registrar ocorrências
- Redução de conflitos internos
- Cumprimento de responsabilidade social

### Para ONGs 

- Centralização das solicitações de resgate
- Priorização baseada em gravidade
- Histórico de atendimentos

### Para o Poder Público  

- Dados estatísticos reais sobre abandono animal
- Apoio à criação de políticas públicas
- Possibilidade de integração com programas municipais e estaduais

## Problema que o Projeto Resolve  

### Atualmente, a comunicação entre condomínios e ONGs ocorre de forma:

- Descentralizada (WhatsApp, ligações, redes sociais)
- Sem padronização de informações
- Sem histórico confiável
- Isso gera atrasos, falhas de comunicação e, em muitos casos, a não realização do resgate.

## Solução Proposta 

Uma plataforma web responsiva, acessível via navegador, que permita:

### Perfis de Usuário 

- Administrador de Condomínio
- ONG / Protetor Independente
- Administrador do Sistema

### Funcionalidades Iniciais  

- Cadastro de ocorrências (animal, local, fotos, observações)
- Geolocalização do resgate
- Status do atendimento (aberto, em andamento, finalizado)
- Histórico de ocorrências

### Funcionalidades Futuras  

- Integração com órgãos públicos
- Relatórios estatísticos
- Painel de dados (dashboard)
- API pública para integração

### Funcionalidades (MVP)

- Autenticação de usuários por perfil
- Cadastro de ocorrências de resgate
- Upload de fotos do animal
- Localização da ocorrência
- Lista de ocorrências abertas
- Aceite de resgate por ONGs
- Atualização de status do resgate
- Histórico de ocorrências
- Painel administrativo

### Impacto Social Esperado

- Aumento do número de resgates realizados
- Diminuição de ocorrências não atendidas
- Organização do trabalho das ONGs
- Base de dados para políticas públicas
- Transparência e rastreabilidade dos resgates

### Tecnologias Planejadas

- **Backend:** Python + Django
- **Frontend:** HTML, CSS, Bootstrap
- **Banco de Dados:** PostgreSQL
- **Autenticação:** Django Auth
- **Infraestrutura:** Docker (futuro)
- **Deploy:** A definir (Railway / Render)

### Governança e Transparência 

- Código aberto (Open Source)
- Histórico público de alterações
- Documentação acessível
- Foco em impacto social, não comercial

## Status do Projeto  

   Fase atual: Planejamento, documentação e UX

## Próximas etapas:

- Desenho das telas
- Definição técnica detalhada
- MVP funcional

## Visão de Crescimento

 Este projeto foi pensado para escalar e se tornar:

- Uma referência nacional em resgate animal
- Um apoio tecnológico para ONGs
- Um instrumento de dados para governos

## Autor

Mayckel Mudri

Projeto desenvolvido como iniciativa social e portfólio técnico.

## Contato

Sugestões, parcerias e apoio institucional são bem-vindos.

“Tecnologia a serviço da vida.”

## Estrutura do Projeto

```text
resgate-animal-plataforma/
├── README.md
├── docs/
│   ├── visao-geral.md
│   ├── impacto-social.md
│   ├── wireframes.md
│   └── roadmap.md
├── backend/
└── .gitignore

