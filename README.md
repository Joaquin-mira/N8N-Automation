# N8N-Automation
Estos son proyectos de automatización de procesos de ciberseguridad en N8N para aprender, practicar y probar conceptos y estrategias
<br><br>
**🐧Linux Threat Hunter**
  <br>
Este proyecto es un sistema SIEM automatizado, privado y procesado por IA local. 
<br>
Consiste en un workflow que extrae logs de sistema de Linux, extrae datos clave y utiliza Llama3 (hosteado localmente) para analizar cada evento en busca de amenazas y anomalías, asignando un valor numérico 1-10 y permitiendo realizar acciones si la severidad de la amenaza es ≥ 7 . Todo este proceso es almacenado en PostgreSQL en la medida en que un evento es detectado y luego procesado por la IA.
<br>
Características
<br>
💻Ingesta automatizada de datos.<br>
🤖Integración con IA local para el análisis de registros.<br>
🛡️100% self-hosted para entornos que requieren privacidad.<br>
🐍Parsing inteligente con Python para limpieza e identificación de datos clave.<br>
🐘Almacenamiento pre y post procesamiento en PostgreSQL para realizar auditorías.
