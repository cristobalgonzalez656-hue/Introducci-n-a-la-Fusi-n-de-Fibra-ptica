# Diagramas editables (Mermaid)

GitHub puede representar los siguientes bloques Mermaid directamente en archivos Markdown. Las imágenes SVG equivalentes están disponibles en `assets/img/`.

## Esquema de proceso

```mermaid
flowchart TD
    A[1. Seguridad y preparación<br/>EPP y residuos] --> B[2. Stripping<br/>Exponer vidrio de 125 μm]
    B --> C[3. Limpieza y cleaving<br/>IPA, paño sin pelusa, corte cercano a 90°]
    C --> D[4. Termofusión<br/>Alineación y arco según fabricante]
    D --> E[5. Protección<br/>Manguito termo-contraíble]
    E --> F[6. Medición y verificación<br/>Continuidad y pérdidas]
    F --> G[Documentar resultados en GitHub]
```

## Mapa mental

```mermaid
mindmap
  root((Repositorio de Fibra Óptica))
    Seguridad
      Lentes de seguridad
      Residuos en contenedor adecuado
      Orden del puesto
    Preparación
      Stripping
      Vidrio de 125 μm
      Limpieza con alcohol isopropílico
      Paño libre de pelusa
    Corte y fusión
      Cleaving cercano a 90°
      Alineación núcleo y cladding
      Arco eléctrico
    Protección
      Manguito termo-contraíble
      Revisión del empalme
    Presupuesto y medición
      Atenuación por km
      Conectores y empalmes
      Margen GPON
      Continuidad y pérdidas
    Repositorio Git
      README.md
      assets/img
      .gitignore
      Commits descriptivos
```
