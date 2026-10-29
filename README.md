# consejo

Skill de Agent Skills para pedir feedback honesto a la IA sin que te dé la razón. Reparte la revisión de un documento, una propuesta, una presentación, un prompt o una decisión entre varios revisores con encargos distintos (experto del dominio, destinatario hostil, sistémico, pragmático y, según el caso, expansionista y editor), los cruza a ciegas y termina con un décimo hombre obligado a discrepar. Devuelve una síntesis sin promediar desacuerdos y una propuesta de cambios lista para aplicar.

## Instalación

Con [skills.sh](https://skills.sh/):

```bash
npx skills add Entaina/consejo-skill --skill consejo
```

Por defecto se instala en el proyecto actual. Con `-g` se instala para tu usuario. La [documentación de la CLI](https://github.com/vercel-labs/skills#readme) explica cómo elegir el agente o actualizar la instalación.

También vale pedírselo a tu agente: «instala la skill de este repositorio» con el enlace. Revisa el contenido de una skill antes de instalarla.

## Uso

Pide «pásame este documento por el consejo» y di qué tiene que conseguir. Sin ese criterio de éxito, la skill te lo pregunta antes de empezar.

## Versiones

Los cambios se gestionan con [release-please](https://github.com/googleapis/release-please-action): los commits convencionales (`feat:`, `fix:`) alimentan una PR de versión con su changelog, y al fusionarla se crea la etiqueta y la release. El comando de instalación instala desde el repositorio; **no fija una release concreta**.

## Contribuir

Usa [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), por ejemplo `feat: añade un rol` o `fix: corrige una instrucción`. Las instrucciones de la skill están en `skills/consejo/SKILL.md`.
