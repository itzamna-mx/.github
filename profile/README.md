<p align="center"><img src="logo.svg" width="120" alt="Itzamná"></p>

<h1 align="center">Itzamná</h1>

<p align="center"><b>Los datos públicos de México, listos para la IA.</b></p>

Itzamná era el dios maya de la sabiduría; según la tradición, inventó la escritura y el calendario, la forma de dejar registro de lo que se sabe. Este proyecto hace lo mismo para los asistentes de IA: les da acceso a la información oficial de México, con la fuente y la fecha de cada dato.

El logo es una greca escalonada, el *xicalcoliuhqui*, que aparece en templos de todo México.

## Servidores MCP

Cada servidor conecta a Claude, ChatGPT, Gemini, Cursor o cualquier cliente MCP con una fuente oficial.

| Servidor | Fuente | Estado |
|---|---|---|
| [mcp-banxico](https://github.com/nanisadw3/mcp-banxico) | Banco de México (SIE): tipo de cambio, inflación, UDIS, TIIE, reservas | ✅ En producción · [PyPI](https://pypi.org/project/mcp-banxico/) · endpoint remoto `https://banxico-mcp.duckdns.org/mcp` |
| mcp-inegi | INEGI: indicadores económicos y directorio de negocios (DENUE) | 🔨 En construcción |
| mcp-sat | SAT: estado de facturas (CFDI) y listas 69 y 69-B | 📋 Planeado |
| mcp-gasolina | Precios de combustibles por estación | 📋 Planeado |

## Principios

- **Ningún dato sin fuente.** Cada respuesta dice de dónde viene (la serie, el registro o el documento oficial) y su fecha de corte, para que cualquiera la pueda verificar.
- **Código abierto y gratis de usar.** Licencia MIT, paquetes en PyPI y endpoints públicos.
- **Hecho en México, en español**, para los casos de uso de aquí.

## Hacia dónde vamos

1. **Servidores MCP** para las principales fuentes públicas de México.
2. **El agente Itzamná:** un asistente que funciona con cualquier modelo (en la nube o local con Ollama) y responde sobre México consultando siempre la fuente oficial.
3. **Más adelante:** un modelo abierto afinado para usar estas herramientas.

---

Creado por [Iñaki Sobera Sotomayor](https://inakisobera.me) · [LinkedIn](https://www.linkedin.com/in/inakisobera/) · [GitHub](https://github.com/nanisadw3)
