# AquaGuard: plataforma de cursos e vigilância aquática

Website responsivo (mobile e desktop) que liga entidades formadoras, concessionários e nadadores-salvadores.
Projeto da unidade curricular **Desenvolvimento para a Web**, Licenciatura em Ciência de Dados para a Gestão, 2026/2027.

## Grupo

- Manuel João Santos: 2024153226
- Tomás Abreu: 2024140672


## Para que serve

O site responde a três necessidades:

1. **Encontrar um curso:** entidades formadoras publicam cursos e quem quer formar-se contacta a entidade.
2. **Pedir nadadores-salvadores:** concessionários de praias, piscinas, hotéis e eventos pedem vigilância.
3. **Escolher uma praia segura:** consultar vigilância, horários e as praias mais seguras e mais perigosas.

Navegação simples (1 a 3 cliques), menu fixo no topo, logótipo que volta sempre ao Início e botão "Voltar" em todas as subpáginas.

## Estrutura do website

```
   Início ....... apresentação, cursos em destaque, praias e perguntas frequentes
   ├── Cursos ... catálogo de cursos e formulário para publicar um curso
   ├── Praias ... lista de praias, ranking de segurança e pedido de vigilância
   └── Contactos  formulário de contacto
```

## Funcionalidades
- menu responsivo;
- catálogo de cursos;
- lista de praias com ranking;
- formulários de contacto e de publicação de curso.

**Básicas**
- Menu fixo, hambúrguer em mobile, botão "Voltar" em todas as subpáginas.
- Catálogo de cursos com filtros, detalhe (programa, requisitos, turmas, vagas) e inscrição com validação.
- Diretório de 31 praias com pesquisa e filtros por região e nível de risco.
- Mapa de Portugal com praias coloridas por risco e rankings das mais seguras e mais perigosas.
- Pedido de vigilância em 4 passos com orçamento em tempo real.
- Candidatura a vagas, formulário de contactos e área pessoal (guardada no navegador).

**Tecnologias**
HTML5 e Tailwind CSS (versão browser).

**Estado do projeto**
E1: grupo, descrição e mockups. E2: estrutura em HTML e responsividade (4 páginas). E3 (a fazer): JavaScript, PHP e base de dados.

**Extras**
- Recomendador de curso, simulador de data/hora de vigilância e planeador de visita à praia.
- Conteúdos de segurança: bandeiras, corrente de retorno, sinais de afogamento, SBV, checklist e quiz.

**Possíveis evoluções**
- Dados reais das praias (APA/Infopraia), com bandeiras e condições do mar em tempo real.
- Backend e base de dados, e-mails de confirmação e pagamento online.
- Praias da Madeira e dos Açores e versão em inglês.
- Operador de Viatura 4x4 e Embarcações de Pequeno Porte.

## Esquemas 

- **Inicio: Mobile**

![Início · Mobile](mockups/inicio-mobile.png)

- **Inicio: Desktop**

![Início · Desktop](mockups/inicio-desktop.png)

- **Praias: Mobile**

![Praias · Mobile](mockups/praias-mobile.png)

- **Praias: Desktop**

![Praias · Desktop](mockups/praias-desktop.png)


## Referências
| Nome | Site |
|---|---|
| Instituto de Socorros a Náufragos / Autoridade Marítima Nacional | https://www.amn.pt |
| APA · Infopraia | https://infopraia.apambiente.pt |
| RNLI · Beach safety | https://rnli.org |
| Surf Life Saving Australia · Beachsafe | https://beachsafe.org.au |
| European Resuscitation Council · Guidelines | https://cprguidelines.eu |
| Unsplash | https://unsplash.com |
| draw.io (diagrams.net) | https://app.diagrams.net |
