# 🏥 Práctico Integrador – Programación Web 2

## 📌 Descripción del Proyecto

Un **sistema hospitalario HIS** (*Hospital Information System*) es una plataforma de software diseñada para gestionar y administrar todas las operaciones y datos de un hospital o clínica. 

📊 **Objetivo principal:** Mejorar la eficiencia, la calidad de la atención médica y la gestión de recursos en el entorno hospitalario.

---

## 🔄 Flujo de Atención de Pacientes

### 📋 Admisión y Recepción

#### 🏷️ Registro y Preparación Previa:
✔ El paciente puede llegar por una **cita programada**, una **derivación médica** o una **emergencia**.
✔ Puede ser derivado por un médico de atención primaria o especialista.

#### 🏥 Recepción y Registro de Datos:
✔ El paciente se dirige a **admisión** y proporciona su información personal, demográfica y de seguros médicos.
✔ Se crea una cuenta nueva si es la primera vez; si no, se actualizan los datos.
✔ Si el paciente viene de **guardia**, solo se registra la internación.

#### 🛏️ Asignación de Habitación:
✔ Se asigna una habitación en la unidad correspondiente (**medicina interna, cirugía, UCI, etc.**).
✔ Las habitaciones pueden alojar **1 o 2 camas**.
✔ Si una habitación tiene **2 camas**, solo se asigna si el otro paciente es del mismo sexo.
✔ La cama debe estar **libre e higienizada** antes de la asignación.

---

## 🩺 Evaluación Inicial por Enfermería

#### 📜 Historial Médico y Antecedentes:
✔ Se verifica la **información personal y de contacto**.
✔ Se recopila el **historial médico**, antecedentes familiares y medicamentos actuales.
✔ Se documenta el **motivo de la internación** y los **síntomas principales**.

#### 📊 Registro de Signos Vitales:
✔ Se miden **presión arterial, frecuencia cardíaca, respiratoria y temperatura corporal**.
✔ Se evalúa el **aspecto general del paciente**.

#### 🏥 Plan de Cuidados Preliminar:
✔ Se elabora un **plan de cuidados**.
✔ Se comunican los hallazgos al **equipo médico**.
✔ Se monitorea continuamente la evolución del paciente.

---

## ⚕️ Evaluación Médica

✔ El equipo médico desarrolla un **plan de atención** personalizado.
✔ Se realizan **evaluaciones periódicas y pruebas diagnósticas** 🩸🩻.
✔ Se administran **tratamientos, terapias y medicamentos** 💊.
✔ Se ajusta el **tratamiento según la evolución del paciente**.

---

## ✅ Alta Hospitalaria

✔ Una vez recuperado, el paciente recibe el **alta hospitalaria**.
✔ Se proporcionan **instrucciones de cuidado posterior, recetas médicas y recomendaciones de seguimiento**.

---

## ⚠️ Consideraciones Adicionales

⚠ **Esta narrativa no es completa.** Los estudiantes deben consultar sobre cualquier duda adicional.
⚠ Se deben considerar **requerimientos implícitos**, como la **cancelación de una admisión** por arrepentimiento o error de carga.

---

## 🎯 Objetivos del TPI

📌 Este trabajo integrador tiene como objetivo que los estudiantes puedan **desarrollar y aplicar** los conocimientos adquiridos en la asignatura mediante un **caso de estudio realista**.
