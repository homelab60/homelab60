# bic

`blockchain + agents`

## contexto

Hoy los agentes de IA trabajan aislados: uno por chat, uno por tarea.
Voy hacia un ecosistema donde colaboran entre sí como un equipo,
cada uno con sus tools, sus skills y su contexto, coordinados para
construir productos reales.

## prompt

Construir las herramientas para llegar ahí: medir lo que producen y mejorarlo con machine learning en cada iteración.

## pirámide

```
         ┌───────────┐
         │ fábricas  │   producen equipos
         └───────────┘
      ┌─────────────────┐
      │     equipos     │   coordinan agentes
      └─────────────────┘
   ┌───────────────────────┐
   │        agentes        │   tools + skills + contexto
   └───────────────────────┘
┌─────────────────────────────┐
│           código            │   acá empezamos: todo a mano
└─────────────────────────────┘
```

## tools

- `typescript` — lo que se ve: interfaces web, dashboards, plantillas base
- `rust` — la infraestructura: servidores MCP, TUIs, tooling de alto rendimiento
- `python` — lo que apoya: pipelines de datos, procesamiento, utilidades

## skills

- `mcp-servers` — servidores MCP que les dan capacidades a los agentes
- `interfaces-para-agentes` — UIs donde personas y agentes trabajan juntos
- `plantillas-base` — bases reutilizables para arrancar productos rápido
- `metricas` — medir, evaluar y mejorar lo que producen los agentes

## indicaciones

- medir todo lo que se produce
- integrar ML siempre que haya oportunidad
- lo que no se puede medir, no se puede mejorar

---

`@homelab60`
