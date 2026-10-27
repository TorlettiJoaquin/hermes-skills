# hermes-skills

Tap de skills para [Hermes Agent](https://hermes-agent.nousresearch.com) (formato agentskills.io). También sirven para OpenClaw y cualquier agente que lea `SKILL.md`.

```bash
hermes skills tap add TorlettiJoaquin/hermes-skills
hermes skills install TorlettiJoaquin/hermes-skills/ar-tools
```

| Skill | Qué hace |
|---|---|
| [ar-tools](skills/ar-tools/SKILL.md) | Validaciones y datos de Argentina (CUIT, CBU, teléfonos, dólar) vía MCP remoto o REST, con créditos prepagos |
| [indices-ar](skills/indices-ar/SKILL.md) | Índices económicos argentinos y ajustes (UVA, CER, ICL, inflación, alquileres, dólar histórico, días hábiles) vía MCP remoto o REST, con créditos prepagos |
| [direcciones-ar](skills/direcciones-ar/SKILL.md) | Direcciones argentinas con el callejero oficial (georef): normalizar y geocodificar, calles, localidades, provincias/partidos/municipios vía MCP remoto o REST, con créditos prepagos |
