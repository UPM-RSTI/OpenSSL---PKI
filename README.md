# Práctica PKI con OpenSSL

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/UPM-RSTI/OpenSSL---PKI/blob/main/Practica_PKI_OpenSSL_2.ipynb)

Práctica guiada de Infraestructura de Clave Pública (PKI) con OpenSSL, en un notebook de Jupyter preparado para Google Colab.

## Contenido

1. **Firma digital:** generación de un par de claves RSA, cifrado de la clave privada, firma y verificación de un fichero.
2. **CA y TLS:** creación de una Autoridad de Certificación propia, emisión de un certificado de servidor y despliegue en Apache con HTTPS.
3. **Revocación y OCSP:** revocación de un certificado y consulta de su estado con un responder OCSP.

## Cómo ejecutarla

1. Pulse el botón **Open in Colab**.
2. En Colab, *Archivo → Guardar una copia en Drive* para conservar sus respuestas.
3. Ejecute las celdas en orden (`Mayús + Intro`).
4. Responda a las preguntas en el cuestionario de Moodle.

El notebook instala los paquetes necesarios y descarga los scripts de la CA (`opensslscripts.tar`). No requiere instalar nada en el equipo del alumno.

## Ficheros

| Fichero | Descripción |
| --- | --- |
| `Practica_PKI_OpenSSL_2.ipynb` | Notebook de la práctica |

---
Departamento de Ingeniería de Sistemas Telemáticos (DIT) · Universidad Politécnica de Madrid
