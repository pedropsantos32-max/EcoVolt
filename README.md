# EcoVolt Analytics

Plataforma SPA para monitoramento, classificação e monetização de baterias
de veículos elétricos, com foco em economia circular e impacto ambiental.

## Funcionalidades

- Diagnóstico de SOH (Estado de Saúde) com classificação automática:
  uso automotivo, segunda vida ou reciclagem
- Dashboard com métricas da frota, sparklines e alertas inteligentes
- Gráfico de curva de degradação histórica + projeção futura
- Marketplace para conexão com empresas compradoras verificadas
- Mapa interativo de parceiros (recicladoras, armazenamento solar, grid)
- Painel de impacto ambiental com equivalências (CO₂, árvores, resíduos)
- Relatório de perfil com abas financeira, ambiental e ESG
- Fluxo de navegação guiado: cadastro → onboarding → plataforma

## Stack

- React (hooks, estado global sem biblioteca externa)
- CSS-in-JS com design tokens e sistema de cores próprio
- SVG puro para gráficos, sparklines e gauge de bateria
- Arquitetura de roteamento leve com pub/sub module-level

## Como rodar

Importe o componente EcoVolt.jsx em qualquer projeto React
com suporte a JSX. Sem dependências externas além do React.
