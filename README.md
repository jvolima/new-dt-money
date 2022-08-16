# DT Money 2.0
## Aplicação feita na trilha de React do Ignite

## Stack
- React
- Typescript
- Styled components
- Vite
- Radix UI
- JSON Server
- react-hook-form
- zod

## Aprendizados novos
- Radix para fazer componentes acessivéis, como Modais, Radio groups, etc.
- Controlled components em formulários que possuem componentes que não são nativos do HTML.
- useContextSelector em vez do useContext para evitar renderizações desnecessárias.
- useCallback para evitar que funções sejam recriadas de forma desnecessária quando o componente for recriado.
- memo (utilizar apenas em componentes muito complexos, que possuem um html extenso) e useMemo (utilizar apenas em váriaveis que são passadas para vários componentes e é feito um cálculo grande para atribuir valor a ela).