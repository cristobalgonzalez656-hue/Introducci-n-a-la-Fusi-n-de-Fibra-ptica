# Introducci-n-a-la-Fusi-n-de-Fibra-ptica
Fibra Optica

<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/94a540e7-2a86-40cc-8b6a-2b119a7a569c" />


# ⚡ Manual Técnico de Laboratorio: Fusión de Fibra Óptica

> **Institución:** INACAP - Sede La Serena
> **Asignatura:** Infraestructura de Redes / Telecomunicaciones
> **Autores:** Cristóbal González y Equipo

![Portada Fusión Fibra Óptica](assets/img/portada_fusion.jpg)

# ⚡ Manual Técnico de Laboratorio: Fusión de Fibra Óptica

> **Institución:** INACAP - Sede La Serena
> **Asignatura:** Infraestructura de Redes / Telecomunicaciones
> **Autores:** Cristóbal González y Equipo

![Portada Fusión Fibra Óptica](assets/img/portada_fusion.jpg)

La presente guía técnica detalla el ciclo completo de preparación y conectorización física de medios de transmisión óptica. Este manual está diseñado para ser consultado directamente en el banco de trabajo, asegurando precisión mecánica y bajas atenuaciones en redes de alta velocidad.

---

## 📖 Glosario Técnico Exprés

*   **Núcleo (Core):** Zona central de la fibra (usualmente 9µm en monomodo) por donde viaja el haz de luz.
*   **Cladding:** Revestimiento externo (125µm) que confina la luz dentro del núcleo mediante reflexión total interna.
*   **Cleaving:** Corte de altísima precisión (ángulo de ~90°) realizado con una cortadora mecánica, vital para una buena fusión.
*   **Atenuación:** Pérdida de potencia de la señal óptica, a menudo causada por suciedad, microcurvaturas o cortes defectuosos.
*   **Stripper:** Pinza especial calibrada para remover las capas protectoras sin dañar el delicado cristal de la fibra.

---

## 🛠️ Guía Paso a Paso: Proceso de Termofusión

A continuación, se detalla el procedimiento estándar de la industria para el empalme de hilos de fibra óptica ("pelos").

![Pasos de Instalación](assets/img/pasos_fibra.jpg)

### Paso 1: Protocolo de Seguridad y Preparación
El manejo de fibra desnuda implica riesgos por los fragmentos microscópicos de vidrio que se desprenden.
*   **Acción:** Colócate los lentes de seguridad antes de comenzar a manipular las herramientas.
*   **Acción:** Dispón de un contenedor rígido específico para desechar de inmediato los residuos de fibra cortada.

> ⚠️ **TIP PEDAGÓGICO (Seguridad):** Nunca pases las manos por la mesa de trabajo para limpiarla ni te frotes los ojos. Los restos de fibra son invisibles, no son detectados por rayos X y son altamente peligrosos si se incrustan en la piel.

### Paso 2: Inserción de la Manga Termocontraíble
Este es el paso que más se olvida en los laboratorios de telecomunicaciones.
*   **Acción:** Antes de pelar o cortar cualquier cable, desliza el protector de empalme (*heat shrink*) en uno de los extremos de la fibra y déjalo alejado de la punta. 
*   *Nota:* Si lo olvidas, tendrás que quebrar la fusión terminada y empezar de cero.

### Paso 3: Stripping (Pelado de la Fibra)
Consiste en remover las protecciones plásticas hasta llegar al revestimiento de vidrio puro.
*   **Acción:** Utiliza la pinza peladora (stripper) en un ángulo de 45 grados respecto al cable.
*   **Acción:** Remueve firmemente aproximadamente 3 a 4 centímetros de la chaqueta exterior, el buffer y el recubrimiento de acrilato (hasta llegar al vidrio de 125 micras).

> ⚠️ **ERROR COMÚN:** Aplicar demasiada fuerza o usar la ranura equivocada del stripper puede mellar, rayar o fracturar internamente el pelo de fibra, lo que causará que se rompa al entrar a la máquina.

### Paso 4: Limpieza de Precisión
La fibra expuesta debe estar inmaculada antes de cortarse y fusionarse.
*   **Acción:** Humedece un paño libre de pelusa (lint-free) con alcohol isopropílico de alta pureza (99%).
*   **Acción:** Abraza la fibra desnuda con el paño y desliza firmemente hacia afuera (hacia la punta), repitiendo un par de veces.

> ⚠️ **TIP PEDAGÓGICO (Limpieza):** Escucharás un ligero "chirrido" (squeak) cuando el vidrio esté completamente limpio. **Regla de oro:** Una vez limpiada la fibra, NUNCA debe tocar ninguna superficie de la mesa ni tus dedos.

### Paso 5: Cleaving (Corte de Precisión)
Un buen corte determina el 80% del éxito de la fusión.
*   **Acción:** Levanta la tapa de la cortadora (cleaver), coloca la fibra limpia en la guía asegurando que el acrilato (la parte plástica) quede en la marca de medida correcta de la regla milimetrada (usualmente 16mm).
*   **Acción:** Cierra la tapa y desliza el carro de la cuchilla de un extremo al otro con un movimiento firme y constante.

> ⚠️ **ERROR COMÚN:** Si el corte queda en diagonal, la máquina de fusión arrojará un error de "Ángulo de corte" (Cleave Angle Error). Debes retirar la fibra, cortar el pedazo dañado y repetir todo desde el Paso 3.

### Paso 6: Alineación y Arco Eléctrico (Fusión)
*   **Acción:** Levanta las tapas protectoras de la fusionadora y coloca cuidadosamente los extremos de ambas fibras ya cortadas en las ranuras en "V" (V-grooves). Las puntas deben quedar cerca de los electrodos centrales, pero sin llegar a tocarse.
*   **Acción:** Cierra la tapa principal. La máquina alineará automáticamente los núcleos usando sus cámaras microscópicas integradas.
*   **Acción:** Si la pantalla muestra que el corte y la alineación son correctos, la máquina (o tú manualmente con el botón SET) disparará el arco eléctrico que derretirá y unirá ambos vidrios a nivel molecular.

### Paso 7: Análisis de Resultados y Horneado
*   **Acción:** Interpreta la pantalla: La máquina estimará la pérdida de inserción de la unión en decibelios (dB). Un valor excelente y aceptable para redes de alta velocidad va de 0.01 dB a 0.03 dB.
*   **Acción:** Abre la tapa, retira con muchísimo cuidado la fibra unida (ahora es una sola pieza) y desliza la manga termocontraíble (*heat shrink*) que pusiste en el Paso 2 justo sobre el punto de vidrio expuesto.
*   **Acción:** Coloca esa sección cubierta en el horno integrado de la máquina y presiona el botón de calentamiento (HEAT). Espera a que termine el pitido, sácala por las partes plásticas y déjala enfriar en la bandeja de metal trasera.

---
*Manual optimizado para visualización rápida en bancos de trabajo de laboratorio.*

---

## 🛠️ Guía Paso a Paso: Proceso de Termofusión

A continuación, se detalla el procedimiento estándar de la industria para el empalme de hilos de fibra óptica ("pelos").

![Pasos de Instalación](assets/img/pasos_fibra.jpg)

### Paso 1: Protocolo de Seguridad y Preparación
El manejo de fibra desnuda implica riesgos por los fragmentos microscópicos de vidrio que se desprenden.
*   **Acción:** Colócate los lentes de seguridad antes de comenzar a manipular las herramientas.
*   **Acción:** Dispón de un contenedor rígido específico para desechar de inmediato los residuos de fibra cortada.

> ⚠️ **TIP PEDAGÓGICO (Seguridad):** Nunca pases las manos por la mesa de trabajo para limpiarla ni te frotes los ojos. Los restos de fibra son invisibles, no son detectados por rayos X y son altamente peligrosos si se incrustan en la piel.

### Paso 2: Inserción de la Manga Termocontraíble
Este es el paso que más se olvida en los laboratorios de telecomunicaciones.
*   **Acción:** Antes de pelar o cortar cualquier cable, desliza el protector de empalme (*heat shrink*) en uno de los extremos de la fibra y déjalo alejado de la punta. 
*   *Nota:* Si lo olvidas, tendrás que quebrar la fusión terminada y empezar de cero.

### Paso 3: Stripping (Pelado de la Fibra)
Consiste en remover las protecciones plásticas hasta llegar al revestimiento de vidrio puro.
*   **Acción:** Utiliza la pinza peladora (stripper) en un ángulo de 45 grados respecto al cable.
*   **Acción:** Remueve firmemente aproximadamente 3 a 4 centímetros de la chaqueta exterior, el buffer y el recubrimiento de acrilato (hasta llegar al vidrio de 125 micras).

> ⚠️ **ERROR COMÚN:** Aplicar demasiada fuerza o usar la ranura equivocada del stripper puede mellar, rayar o fracturar internamente el pelo de fibra, lo que causará que se rompa al entrar a la máquina.

### Paso 4: Limpieza de Precisión
La fibra expuesta debe estar inmaculada antes de cortarse y fusionarse.
*   **Acción:** Humedece un paño libre de pelusa (lint-free) con alcohol isopropílico de alta pureza (99%).
*   **Acción:** Abraza la fibra desnuda con el paño y desliza firmemente hacia afuera (hacia la punta), repitiendo un par de veces.

> ⚠️ **TIP PEDAGÓGICO (Limpieza):** Escucharás un ligero "chirrido" (squeak) cuando el vidrio esté completamente limpio. **Regla de oro:** Una vez limpiada la fibra, NUNCA debe tocar ninguna superficie de la mesa ni tus dedos.

### Paso 5: Cleaving (Corte de Precisión)
Un buen corte determina el 80% del éxito de la fusión.
*   **Acción:** Levanta la tapa de la cortadora (cleaver), coloca la fibra limpia en la guía asegurando que el acrilato (la parte plástica) quede en la marca de medida correcta de la regla milimetrada (usualmente 16mm).
*   **Acción:** Cierra la tapa y desliza el carro de la cuchilla de un extremo al otro con un movimiento firme y constante.

> ⚠️ **ERROR COMÚN:** Si el corte queda en diagonal, la máquina de fusión arrojará un error de "Ángulo de corte" (Cleave Angle Error). Debes retirar la fibra, cortar el pedazo dañado y repetir todo desde el Paso 3.

### Paso 6: Alineación y Arco Eléctrico (Fusión)
*   **Acción:** Levanta las tapas protectoras de la fusionadora y coloca cuidadosamente los extremos de ambas fibras ya cortadas en las ranuras en "V" (V-grooves). Las puntas deben quedar cerca de los electrodos centrales, pero sin llegar a tocarse.
*   **Acción:** Cierra la tapa principal. La máquina alineará automáticamente los núcleos usando sus cámaras microscópicas integradas.
*   **Acción:** Si la pantalla muestra que el corte y la alineación son correctos, la máquina (o tú manualmente con el botón SET) disparará el arco eléctrico que derretirá y unirá ambos vidrios a nivel molecular.

### Paso 7: Análisis de Resultados y Horneado
*   **Acción:** Interpreta la pantalla: La máquina estimará la pérdida de inserción de la unión en decibelios (dB). Un valor excelente y aceptable para redes de alta velocidad va de 0.01 dB a 0.03 dB.
*   **Acción:** Abre la tapa, retira con muchísimo cuidado la fibra unida (ahora es una sola pieza) y desliza la manga termocontraíble (*heat shrink*) que pusiste en el Paso 2 justo sobre el punto de vidrio expuesto.
*   **Acción:** Coloca esa sección cubierta en el horno integrado de la máquina y presiona el botón de calentamiento (HEAT). Espera a que termine el pitido, sácala por las partes plásticas y déjala enfriar en la bandeja de metal trasera.

---
*Manual optimizado para visualización rápida en bancos de trabajo de laboratorio.*
