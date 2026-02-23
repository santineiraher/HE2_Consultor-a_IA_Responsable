# HE2 - Consultoria e IA responsable 🚀🤖

Curso orientado a economistas–consultores para formular, evaluar y acompañar proyectos de analitica e IA en economia, con enfasis en valor economico y social, riesgos eticos, gobernanza y cumplimiento.

## Politica de uso de IA 🧠✅

Se permite el uso de herramientas de IA como apoyo, pero no como sustituto del pensamiento critico y la resolucion autonoma de problemas. El uso indiscriminado tendra penalizaciones segun los lineamientos de cada taller.

## Resultados de aprendizaje (resumen) 🎯📚

- Formular preguntas problema y objetivos analiticos desde necesidades de negocio o politica publica. 🧩
- Diseñar soluciones conceptuales de datos/IA con datos, modelos y metricas coherentes. 🛠️
- Valorar proyectos con flujos de caja, VPN, escenarios y sensibilidad. 💰
- Identificar riesgos eticos y proponer mitigaciones y gobernanza. 🛡️
- Comunicar resultados a audiencias no tecnicas y colaborar en equipos interdisciplinarios. 🤝

## Estructura 🗂️

Las presentaciones se almacenan en carpetas por semana en la raiz del repositorio:

| Semana | Fechas | Tema | Materiales |
| --- | --- | --- | --- |
| Semana 01 📌 | 19-23 Ene | Rol del economista-consultor en IA / De la necesidad del cliente a la pregunta problema | [Carpeta](Semana%2001) |
| Semana 02 📊 | 26-30 Ene | Ciclo de vida de datos: calidad / feature engineering / inspeccion | [Carpeta](Semana%2002) |
| Semana 03 🧠 | 2-6 Feb | ML clasico (supervisado) y econometria: recorderis y cambio de paradigma | [Carpeta](Semana%2003) |
| Semana 04 🤖 | 9-13 Feb | ML clasico (supervisado) - clasificacion: KNN y SVM | [Carpeta](Semana%2004) |
| Semana 05 🌳 | 16-20 Feb | Arboles y ensambles: CART, RF, XGBoost, interpretabilidad | [Carpeta](Semana%2005) |
| Semana 06 🧩 | 23-27 Feb | ML no supervisado y segmentacion de usuarios | [Carpeta](Semana%2006) |
| Semana 07 💬 | 2-6 Mar | IA generativa y NLP como herramientas para consultoria | [Carpeta](Semana%2007) |
| Semana 08 🧠 | 9-13 Mar | Frontera de la IA actual + parcial | [Carpeta](Semana%2008) |
| Semana 09 🧭 | 23-27 Mar | De los modelos al proyecto: formulacion formal de proyectos de IA | [Carpeta](Semana%2009) |
| Semana 10 💰 | 6-10 Abr | Identificacion de valor economico y social de proyectos de IA | [Carpeta](Semana%2010) |
| Semana 11 📈 | 13-17 Abr | VPN, TIR, sensibilidad y escenarios; gobernanza y documentacion | [Carpeta](Semana%2011) |
| Semana 12 🛡️ | 20-24 Abr | Auditoria e impact assessment; cumplimiento regulatorio en IA | [Carpeta](Semana%2012) |

Notas del calendario 📅:
- Semana de receso: 16-20 Mar.
- Semana Santa: 30 Mar - 3 Abr.

## Recursos extra 🎁📎

Estos recursos incluyen notebooks introductorios de Python y presentaciones con la configuracion del entorno y requisitos de trabajo.

- Taller de Python (notebooks): [Carpeta](Recursos%20extra/Clases%20taller%20de%20python)
  - [Clase 1](Recursos%20extra/Clases%20taller%20de%20python/Clase_1.ipynb)
  - [Clase 2](Recursos%20extra/Clases%20taller%20de%20python/Clase_2.ipynb)
  - [Clase 3](Recursos%20extra/Clases%20taller%20de%20python/Clase_3.ipynb)
  - [Clase 4](Recursos%20extra/Clases%20taller%20de%20python/Clase_4.ipynb)
- Ambientes de trabajo (presentacion): [HE2__Ambientes_de_Trabajo_para_consultoria.pdf](Recursos%20extra/Sobre%20los%20ambientes%20de%20trabajo%20en%20consultor%C3%ADa/HE2__Ambientes_de_Trabajo_para_consultor%C3%ADa.pdf)


## Uso ✅

Agrega las presentaciones y materiales correspondientes dentro de la carpeta de cada semana.

## Entorno de trabajo (conda / pip) 🧪

Para evitar conflictos con `base`, se recomienda un entorno dedicado.

### Conda (recomendado)

```bash
conda env create -f conda_environment.yml
conda activate pce-2026
python -m ipykernel install --user --name pce-2026 --display-name "PCE 2026"
```

### Pip

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Licencia: material académico de la Universidad de los Andes. La compartida del repositorio y sus contenidos debe realizarse solo con previa autorizacion de profesores.

Contactos: `s.neira10@uniandes.edu.co`, `cm.bernal10@uniandes.edu.co` `ga.castillo@uniandes.edu.co`.

## Referencias 📚

- Hastie, T., Tibshirani, R., & Friedman, J. (2009). [The Elements of Statistical Learning: Data Mining, Inference, and Prediction (2ª ed.)](https://link.springer.com/book/10.1007/978-0-387-84858-7). Springer. ISBN: 978-0-387-84858-7
