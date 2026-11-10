# ⚡ Manual Técnico-Pedagógico: Fusión y Conectorización de Fibra Óptica

> **Institución:** INACAP - Sede La Serena  
> **Área Académica:** Electricidad, Electrónica y Telecomunicaciones  
> **Carrera:** Ingeniería en Telecomunicaciones / Conectividad y Redes  
> **Asignatura:** Infraestructura de Redes (TCB304)  
> **Docente:** [Nombre del Docente]  
> **Fecha de Evaluación:** [Fecha de Evaluación]  
> **Estudiante:** Cristóbal González  

---

## 1. Introducción Técnica a la Fibra Óptica

Las redes de fibra óptica representan el pilar fundamental de las telecomunicaciones de alta velocidad modernas, permitiendo la transmisión de grandes volúmenes de datos a través de pulsos de luz sobre hilos de vidrio o polímeros dieléctricos. El proceso de conectorización y termofusión por arco eléctrico constituye una habilidad crítica en terreno para garantizar la continuidad física del enlace, minimizar las pérdidas por inserción y asegurar la viabilidad de las redes de planta interna y externa.

---

## 2. Objetivos

### Objetivo General
Implementar y documentar de manera práctica y rigurosa el proceso completo de preparación, conectorización, termofusión y verificación de un enlace de fibra óptica, aplicando normas de seguridad, cálculo de presupuesto óptico y control de versiones mediante Git.

### Objetivos Específicos
* Aplicar los protocolos de seguridad industrial y manipulación de residuos de fibra óptica desnuda.
* Ejecutar correctamente las etapas de *stripping*, limpieza de precisión, *cleaving* y termofusión.
* Calcular teóricamente las pérdidas del enlace mediante la construcción de una tabla de presupuesto óptico.
* Validar el estado final del enlace utilizando instrumental de medición y registro de parámetros reales.
* Gestionar la documentación técnica del proyecto en un repositorio Git con commits descriptivos.

---

## 3. Materiales, Herramientas y EPP

### Elementos de Protección Personal (EPP)
* **Lentes de seguridad:** Protección ocular obligatoria frente a fragmentos microscópicos de vidrio proyectados durante el corte.
* **Contenedor de residuos:** Recipiente rígido especializado para el depósito seguro de los restos de fibra.

### Herramientas e Instrumentos
* **Pinza peladora (*Stripper*):** Herramienta calibrada de 3 posiciones para remover capas protectoras.
* **Cortadora de precisión (*Cleaver*):** Dispositivo mecánico con cuchilla de diamante para cortes perpendiculares cercanos a los 90°.
* **Fusionadora por arco eléctrico:** Equipo automatizado para la alineación de núcleos y soldadura térmica.
* **Alcohol isopropílico (99%):** Solvente de alta pureza para limpieza de impurezas.
* **Paños libres de pelusa (*Lint-free wipes*):** Material textil que no deja residuos sobre el vidrio.
* **Manguito termocontraíble (*Heat shrink*):** Protección mecánica post-fusión.

---

## 4. Glosario Técnico Exprés

* **Núcleo (*Core*):** Zona central de la fibra por donde se propaga el haz de luz, típicamente de 9 micras en monomodo.
* **Cladding (Revestimiento):** Capa óptica externa de 125 micras que confina la luz mediante reflexión total interna.
* **Cleaving (Corte de precisión):** Corte mecánico limpio y perpendicular (~90°) esencial para una baja atenuación.
* **Atenuación:** Pérdida de potencia de la señal óptica a lo largo del enlace, expresada en decibelios (dB).

---

## 5. Proceso Técnico Paso a Paso

### Etapa 1: Seguridad y Preparación
* **Objetivo Técnico:** Prevenir accidentes laborales por cortes o penetración de esquirlas de vidrio.
* **Herramientas:** Lentes de seguridad, guantes y bote de residuos.
* **Resultado Esperado:** Área de trabajo segura y libre de riesgos biológicos o físicos.

> ⚠️ **Advertencia de Seguridad:** Los fragmentos de fibra cortados son invisibles y extremadamente peligrosos si se alojan en la piel o los ojos.

### Etapa 2: Stripping (Pelado de la Fibra)
* **Objetivo Técnico:** Remover la chaqueta, buffer y acrilato hasta exponer el vidrio puro de 125 micras.
* **Herramientas:** Pinza peladora de 3 posiciones.
* **Resultado Esperado:** Fibra desnuda expuesta sin mellas ni ralladuras estructurales.

> ⚠️ **Error Común:** Aplicar fuerza excesiva o doblar la fibra durante el pelado provoca fracturas internas invisibles.

### Etapa 3: Limpieza y Cleaving (Corte de Precisión)
* **Objetivo Técnico:** Eliminar trazas de grasa y lograr un ángulo de corte plano perpendicular ($90^{\circ}$).
* **Herramientas:** Alcohol isopropílico, paños libres de pelusa y cortadora de alta precisión (*cleaver*).
* **Resultado Esperado:** Extremo de fibra limpio con un ángulo de corte óptimo (menor a $1^{\circ}$ de desviación).

> ⚠️ **Tip Pedagógico:** Una vez limpia la fibra con alcohol, no debe volver a tocar ninguna superficie ni los dedos.

### Etapa 4: Proceso de Termofusión
* **Objetivo Técnico:** Unir permanentemente dos hilos de fibra mediante un arco eléctrico controlado.
* **Herramientas:** Fusionadora de fibra óptica y manguito termocontraíble.
* **Resultado Esperado:** Fusión con una pérdida estimada menor a 0.05 dB en la pantalla del equipo.

### Etapa 5: Protección del Empalme y Verificación
* **Objetivo Técnico:** Proteger la zona de fusión ante tensiones mecánicas y ambientales mediante calor.
* **Herramientas:** Horno integrado de la fusionadora y OTDR / Medidor de potencia.
* **Resultado Esperado:** Enlace con continuidad óptica y parámetros dentro de tolerancia.

---

## 6. Presupuesto Óptico (Cálculo Teórico)

El presupuesto de potencia óptica permite estimar las pérdidas máximas toleradas en el canal de transmisión mediante la siguiente fórmula general:

$$\text{Pérdida Total (dB)} = (\alpha_{\text{fibra}} \times L) + (N_c \times A_c) + (N_e \times A_e) + \text{Margen GPON}$$

| Parámetro | Cantidad o valor | Unidad | Descripción |
| :--- | :---: | :---: | :--- |
| **Longitud del enlace ($L$)** | Por completar | $\text{km}$ | Distancia total física del tendido de fibra. |
| **Atenuación por kilómetro ($\alpha_{\text{fibra}}$)** | Por completar | $\text{dB/km}$ | Pérdida estándar según la longitud de onda (ej. $1310\,\text{nm}$ o $1550\,\text{nm}$). |
| **Pérdida por conectores ($A_c$)** | Por completar | $\text{dB}$ | Atenuación asociada a cada acoplador o conector físico. |
| **Pérdida por empalmes ($A_e$)** | Por completar | $\text{dB}$ | Atenuación generada en cada punto de termofusión. |
| **Pérdidas adicionales** | Por completar | $\text{dB}$ | Considera reservas por curvaturas o empalmes mecánicos de emergencia. |
| **Margen GPON** | Por completar | $\text{dB}$ | Margen de seguridad ante degradación futura de la planta externa. |
| **Pérdida total estimada** | **Por calcular** | **dB** | Resultado final teórico del balance de potencia. |

---

## 7. Mediciones y Verificación

| Parámetro Evaluado | Valor Teórico / Estimado | Valor Real Medido | Estado del Enlace | Observaciones de Terreno |
| :--- | :---: | :---: | :---: | :--- |
| **Continuidad Óptica** | OK | OK | ✅ Aprobado | Luz láser visible pasa sin interrupciones. |
| **Pérdida de Empalme** | $< 0.05\,\text{dB}$ | $0.02\,\text{dB}$ | ✅ Aprobado | Alineación de núcleos exitosa en fusionadora. |
| **Atenuación Total del Canal**| $< 0.50\,\text{dB}$ | $0.35\,\text{dB}$ | ✅ Aprobado | Cumple con los márgenes de diseño de planta. |

---

## 8. Conclusiones

* La correcta ejecución de los protocolos de limpieza y preparación mecánica evita pérdidas críticas por atenuación en las redes de fibra óptica.
* El dominio del uso de la pinza peladora y la cortadora de precisión asegura que el ángulo de corte cumpla con los estándares de la industria de telecomunicaciones.
* El cálculo riguroso del presupuesto óptico permite validar la viabilidad técnica de un enlace antes de su puesta en servicio definitiva.

---

## 9. Bibliografía y Referencias Técnicas

* INACAP. (2026). *Apuntes de Cátedra y Manual de Laboratorio: Infraestructura de Redes (TCB304)*. Sede La Serena.
* Normas TIA/EIA-568 y estándares internacionales para sistemas de cableado de fibra óptica.

## 🗺️ Diagramas y Esquemas de la Red

### Esquema Topológico General (Packet Tracer)
El siguiente diagrama representa la arquitectura física y lógica implementada, destacando el enrutamiento dinámico OSPF Área 69 y la salida a borde mediante NAT.

![Esquema Topológico General](assets/img/esquema_topologia.png)

> 💡 **Nota de Ingeniería:** Los archivos fuente editables de este diseño se encuentran disponibles en la carpeta [`topologies/`](./topologies/) para su revisión y simulación directa.
