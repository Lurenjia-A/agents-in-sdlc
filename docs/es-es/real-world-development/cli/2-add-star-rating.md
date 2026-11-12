---
title: "Lección 2 - Añade valoraciones con estrellas: una victoria rápida"
description: "Usa Copilot CLI para hacer un cambio pequeño en las tarjetas de juegos, revisarlo en un navegador reenviado y combinar tu primera pull request."
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

Ahora que has instalado Copilot CLI y probado una conversación, es hora de hacer tu primer cambio en el proyecto. Las tarjetas de la página principal mostrarán la valoración por estrellas que ya existe en los datos.

En esta lección:

- iniciarás una conversación centrada en una rama de funcionalidad;
- pedirás al agente que haga un cambio pequeño;
- revisarás el cambio con `/diff`;
- ejecutarás la aplicación y confirmarás el resultado en el navegador;
- abrirás y combinarás tu primera pull request.

## Escenario

Cada juego de Tailspin Toys puede tener una valoración por estrellas y ya aparece en la página de detalles. Pide al agente que muestre la valoración existente en cada tarjeta y que cubra ambos estados con pruebas.

## Inicia una conversación

1. Vuelve a tu codespace.
2. Si el terminal no está abierto, presiona <kbd>Control</kbd>+<kbd>\`</kbd> (Mac) o <kbd>Ctrl</kbd>+<kbd>\`</kbd> (Windows/Linux).
3. Inicia Copilot:

   ```bash
   copilot --yolo
   ```

4. Usa `/new` y presiona <kbd>Enter</kbd>.
5. Envía este prompt:

   ```plaintext
   Show each game's starRating out of 5 in the game cards on the list page. If the rating is null, show "No rating yet". Keep the card layout as it is, add tests, and run the relevant checks.
   ```

## Revisa el diff

Usa `/diff` y confirma que se muestran la valoración numérica y `No rating yet` cuando `starRating` es `null`. Revisa también las pruebas y los resultados de las comprobaciones.

## Abre y combina tu primera pull request

Pide a Copilot que confirme los cambios y usa `/pr create`. Revisa la pull request y sus comprobaciones, selecciona **Merge pull request** cuando todo sea correcto y actualiza tu rama local:

```bash
git checkout main
git pull
```

Continúa con [el modo agente y la planificación][next-lesson].

[next-lesson]: ../3-agent-modes/
