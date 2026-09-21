# Horas extras · Prototipo funcional (GLPI → Nómina)

Prototipo navegable del submódulo **Horas Extras** (historias HE-GLPI-01 a HE-GLPI-05).
Es un solo archivo `index.html`, sin backend: los datos son de demostración y se guardan en el navegador (localStorage).

## Cómo usarlo
- Cambia el rol con **"Ver como"**: Colaborador, Coordinador SAC o Recursos Humanos.
- **Reiniciar** (barra lateral) devuelve los datos al estado inicial.

## Guion de validación
| Historia | Qué probar |
|---|---|
| HE-GLPI-01 | En *Tickets GLPI*, cerrar el #48398 y sincronizar; los ya procesados no se duplican. |
| HE-GLPI-02 | La tarea Standby del #48240 queda "Descartada". |
| HE-GLPI-03 | El #48360 cruza la medianoche y se parte por día; Jorge Pérez usa turno 8–17. |
| HE-GLPI-04 | Detalle con origen GLPI y trazabilidad; el colaborador solo ve lo suyo. |
| HE-GLPI-05 | Corregir a *jperez* en GLPI, pedir a RRHH la corrección de *avera* y revalidar. |

## Publicar en GitHub Pages
1. Sube estos archivos a la raíz de un repositorio.
2. *Settings → Pages → Build and deployment*: Source **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. La URL queda como `https://<usuario>.github.io/<repositorio>/`.
