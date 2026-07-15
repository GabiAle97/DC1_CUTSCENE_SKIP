# Dino Crisis Early Cutscene Skip mod

#### (Elija su idioma abajo / Choose your language below)
[![Español](https://img.shields.io/badge/Language-Español-red)](README.md)
[![English](https://img.shields.io/badge/Language-English-blue)](README.en.md)
[![Código Fuente](https://shields.io/badge/Código-Fuente-green)](script.lua)
[![Seguridad](https://shields.io/badge/Análisis-Seguridad-yellow)](https://www.virustotal.com/gui/file/ae29bb54a3a3d8caf429609da6da49d1c023539f0c192d366cf70e54dbd46afb/detection)

## SOBRE EL SCRIPT

LUA Script de Cheat Engine que detecta cutscenes y las skippea. Principalmente se basa en skips completos, y en la menor cantidad de escenas aceleradas posibles (como animaciones de escalera, puertas, movimiento de puzzles, escenas imposibles de saltear, etc). Actualmente, es posible terminar tanto la ruta Any% como la ruta Best Ending en +- 30 minutos. 

## NOTA IMPORTANTE

Este script recolecta el número de veces que que se skipean escenas durante una run completa para decidir si está habilitado a skipear o no, o si debe cargar un objeto en inventario, o si debe cambiar IDs internos de decision, por lo que cargar un juego guardado con el cutscene skip, salvo muy pocas excepciones, puede ocasionar errores en la ruta que se quiere tomar, incluso generar crashes. De momento, evitar el uso de partidas guardadas hasta que se pueda solventar este problema.

## CÓMO USAR

Dispones de dos métodos totalmente seguros para utilizar este mod según tus preferencias:

### Opción 1: Tabla Tradicional (Recomendado para máxima transparencia)
1. Cargar el juego de forma habitual.
2. Abrir **Cheat Engine** y cargar el archivo `DINO.CT` incluido en este repositorio.
3. Aceptar la ejecución del script para asociar el LUA con el juego.

*Nota: Para cumplir con los estándares de la comunidad y facilitar la indexación, el código fuente completo e independiente de este sistema lógico está expuesto en texto plano en el archivo [`script.lua`](script.lua) para auditoría pública.*

### Opción 2: Versión Autónoma (Sin Cheat Engine de fondo)
Si no querés abrir Cheat Engine en cada partida, podés utilizar directamente el ejecutable independiente **`dinoskip.EXE`**.

⚠️ **AVISO SOBRE FALSOS POSITIVOS:** Al haber sido generado mediante el compilador nativo de scripts de Cheat Engine, este ejecutable empaqueta internamente partes de dicha herramienta para automatizar los ganchos de memoria. Debido a esto, algunos motores de antivirus heurísticos lo marcarán erróneamente como una amenaza potencial (`HackTool` o `Generic.Trj`). 
* El comportamiento es 100% seguro y actúa únicamente sobre las direcciones de memoria propias de *Dino Crisis*.
* Podés comprobar la legitimidad del archivo revisando el [Análisis Público de VirusTotal](https://virustotal.com).
* Para utilizarlo, es necesario agregar el `.exe` a las excepciones de tu antivirus.

---

Combinar con [DinoReady Patch DoorSkip](https://www.speedrun.com/dino1/resources/kzgcz) para una experiencia muchísimo más fluida.

## AGRADECIMIENTOS

- [iiLanceLM](https://www.twitch.tv/iilancelm) y [MattGael](https://www.twitch.tv/mattgael) por ayudar con el testeo, la guía y la promoción del script.
- [EyeOfTheMind86](https://fearlessrevolution.com/viewtopic.php?t=27598) por su Cheat Table, de donde saqué un par de direcciones útiles
- Valka por darme fuerzas

## PROPINAS

Querés tirarme una monedita? Podés hacerlo desde acá:
- Fuera de Argentina: [PATREON](https://www.patreon.com/cw/EmuTesting)
- En Argentina: [CAFECITO](https://cafecito.app/gabimufas97) o MERCADO PAGO (alias: GabiAle97)
