\documentclass{article}

% Language setting
% Replace `english' with e.g. `spanish' to change the document language
\usepackage[english]{babel}

% Set page size and margins
% Replace `letterpaper' with`a4paper' for UK/EU standard size
\usepackage[letterpaper,top=2cm,bottom=2cm,left=3cm,right=3cm,marginparwidth=1.75cm]{geometry}

% Useful packages
\usepackage{amsmath}
\usepackage{graphicx}
\usepackage[colorlinks=true, allcolors=blue]{hyperref}

\title{Inteligencia artificial y aprendizaje automático en
medicina
Artificial intelligence and machine learning in medicine}
\author{ALAY CRUZ EDITH MARIBEL}

\begin{document}
\maketitle
\begin{abstract}
Machine learning is a powerful branch of Artificial Intelligence that has been
used successfully in different industries. In the last few years with the
increasing availability of clinical data stored in electronic format, the medical
field has become an ideal environment for the development and application
of these technologies. Machine learning has the potential to improve healthcare system by analyzing millions of clinical data to create prognostic,
screening and diagnostic models. However, even though it is evident that
the use of these algorithms can improve the quality of healthcare systems
and patient’s life, an appropriate validation process is needed in order to
implement these technologies into the clinical practice. 
 
KEYWORDS: machine learning; artificial intelligence; quality of healthcare.
\end{abstract}

\section{\textbf{INTRODUCCIÓN}}
En los inicios de la medicina, los clínicos trabajaban en grupo para resolver problemas complejos. Hoy en día, la medicina es aún más compleja, con múltiples terapias y datos que superan la capacidad humana. Por ello, se requiere el uso de herramientas como el aprendizaje automático, que puede integrar grandes cantidades de datos, reconocer patrones y optimizar la atención médica. Aunque ya es exitoso en áreas como finanzas y mercadotecnia, su uso en medicina enfrenta desafíos legales, éticos y de desarrollo. Este artículo busca introducir el aprendizaje automático en salud, sus aplicaciones y los retos para su implementación.
\section{\textbf{MÉTODOS }}
Se obtuvieron artículos con fecha de
publicación menor a 5 años de
antigüedad en base de datos como
PubMed, Medline, DynaMed,
DynaMedPlus y de buscadores como
Google Scholar. Para la búsqueda de los
artículos se utilizaron términos de
búsqueda como “Machine learning in
Medicine” y “Artificial Intelligence in
Medicine”. Posteriormente se filtraron con el fin de utilizar los de mayor afinidad
al contenido de este artículo. Y
finalmente se revisaron los artículos
completos que contenían información de
mayor interés para el cumplimiento de
los objetivos de este escrito.
\section{\textbf{FUNDAMENTOS DE MACHINE LEARNING }}
El aprendizaje automático, término acuñado por Arthur Samuel en 1959, se refiere a una tecnología que permite a las computadoras aprender y mejorar en tareas específicas sin recibir instrucciones explícitas. Samuel lo demostró al programar un juego de damas que podía mejorar con la experiencia. El aprendizaje automático es una rama de la inteligencia artificial que utiliza algoritmos y técnicas estadísticas para analizar datos, aprender de errores y hacer predicciones. A diferencia de métodos estadísticos convencionales que buscan hacer inferencias, el aprendizaje automático se enfoca en comprender y aprender las relaciones entre variables a través de ejemplos y datos.
\section{CATEGORÍAS DE MACHINE LEARNING}
Los tres tipos principales de aprendizaje automático son:

Aprendizaje supervisado: El modelo se entrena con un conjunto de datos etiquetados, donde las respuestas correctas están incluidas. El objetivo es que el modelo aprenda a predecir el resultado para nuevos datos a partir de la experiencia previa. Es útil en problemas como la clasificación y la regresión.

Aprendizaje no supervisado: No se proporcionan etiquetas ni respuestas correctas. El modelo intenta encontrar patrones o estructuras ocultas en los datos. Se utiliza en tareas como la agrupación (clustering) y la reducción de dimensionalidad.

Aprendizaje por refuerzo: El modelo aprende a través de prueba y error, recibiendo recompensas o castigos según las acciones que toma en un entorno. Es común en sistemas de control, videojuegos y robots, donde se necesita tomar decisiones secuenciales.
\subsection{\textbf{CONSTRUCCIÓN DE UN SISTEMA DE MACHINE LEARNING}}

La construcción de un sistema de machine learning se detalla en los siguientes pasos:

Preprocesamiento: Se verifica la calidad de los datos, reduciendo los ruidos, eliminando características irrelevantes y corrigiendo problemas de inconsistencias. Este paso genera la base de datos adecuada para entrenar el modelo.

Cálculo de características: Se identifican las características clave para la toma de decisiones, asignando un valor numérico a cada variable. Estas características pueden ser visuales o numéricas, dependiendo del tipo de datos.

Selección de características: Se eligen las características más relevantes para evitar que el modelo se sobreajuste o pierda precisión. Solo las características con mayor impacto en el modelo son seleccionadas.

Entrenamiento, prueba y validación: El conjunto de datos se divide en diferentes subconjuntos para entrenar el modelo y luego validar su rendimiento. Esto asegura que el sistema pueda generalizar y realizar predicciones precisas.
\subsection{\textbf{ÁREAS DE IMPLEMENTACIÓN DE MACHINE LEARNING}}

1. Pronóstico
El uso de algoritmos de aprendizaje automático permite prevenir brotes de enfermedades y tendencias en la salud pública. Estos modelos analizan grandes volúmenes de datos históricos para identificar patrones que pueden predecir la aparición de enfermedades, lo que ayuda a los sistemas de salud a preparar y responder adecuadamente.
2. Tamizaje y diagnóstico
Los sistemas de aprendizaje automático están mejorando significativamente la precisión en el diagnóstico médico. A través del análisis de imágenes médicas, como radiografías y resonancias magnéticas, estos modelos pueden detectar anomalías que podrían pasar desapercibidas para el ojo humano. Esto no solo agiliza el proceso de diagnóstico, sino que también aumenta la tasa de detección temprana de enfermedades graves.
3. Reducción de Carga Clínica
La implementación de machine learning puede optimizar la carga clínica al automatizar tareas administrativas y clínicas. Esto incluye la gestión de registros médicos, programación de citas y seguimiento del tratamiento, permitiendo a los profesionales de la salud centrados más en la atención al paciente y menos en tareas burocráticas.
4. Acceso a Sistemas de Salud
El aprendizaje automático también juega un papel crucial en mejorar el acceso a los servicios de salud. Al analizar datos sobre patrones demográficos y geográficos, se pueden identificar áreas desatendidas o con acceso limitado a servicios médicos. Esto permite a las autoridades sanitarias implementar estrategias más efectivas para garantizar que todos los ciudadanos tengan acceso a atención médica adecuada.
Estas áreas no solo mejoran la eficiencia del sistema sanitario, sino que también contribuyen a una atención más personalizada y centrada en el paciente, lo que es esencial para lograr mejores resultados en salud pública.
\section{TRATAMIENTO }
Los modelos de machine learning pueden aprender a identificar el mejor
tratamiento para un paciente, basándose en información objetiva. Asimismo,
herramientas de aprendizaje automático pueden mejorar el descubrimiento y desarrollo de nuevos medicamentos.
Por ejemplo, se aplican nuevas técnicas de aprendizaje automático en detección
virtual (campo computacional que ayuda en estudios experimentales a detectar
interacciones desconocidas en nuevos fármacos), sin embargo, hoy en día el
rendimiento de predicción continúa siendo bajo La reducción de la carga clínica y el acceso al sistema de salud son dos de los principales beneficios que el machine learning puede ofrecer en medicina:

\begin{enumerate}
    \item \textbf{Reducción de la carga clínica:} El machine learning puede automatizar tareas repetitivas, como la interpretación de imágenes médicas y la gestión de datos, lo que permite a los médicos enfocarse en casos más complejos y mejorar la eficiencia en el diagnóstico y tratamiento. Esto disminuye la sobrecarga de trabajo y acelera la atención al paciente.

    \item \textbf{Acceso al sistema de salud:} Al facilitar diagnósticos más rápidos y precisos, especialmente en áreas con recursos limitados, el machine learning mejora el acceso a la atención médica de calidad. Los sistemas automatizados también pueden ayudar a identificar enfermedades en etapas tempranas, permitiendo tratamientos más efectivos y mejorando los resultados de salud en poblaciones vulnerables.
\end{enumerate}

\subsection{\textbf{LIMITACIONES Y DESAFÍOS}}
Recopilación de Datos de Alta Calidad
La efectividad de los modelos de aprendizaje automático depende en gran medida de la calidad de los datos utilizados.

1. La \textbf{recopilación} de \textbf{datos} precisos y representativos es un desafío constante, ya que muchos sistemas de salud carecen de bases de datos integradas y estandarizadas. Además, la falta de datos estructurados puede dificultar el entrenamiento adecuado de los modelos, lo que resulta en predicciones inexactas o sesgadas.

\textbf{2. Traducción de resultados
}La interpretación y traducción de los resultados generados por algoritmos de aprendizaje automático a un lenguaje comprensible para los profesionales médicos es crucial. Sin embargo, muchos modelos son considerados "cajas negras", lo que significa que sus decisiones son difíciles de entender y explicar. Esto puede generar desconfianza entre los médicos y limitar la adopción de estas tecnologías en la práctica clínica.

\textbf{3. Normas y Legislaciones
}El entorno regulatorio en el que operan las tecnologías de aprendizaje automático es complejo y varía entre regiones. Las normativas sobre privacidad de datos, como el GDPR en Europa, imponen restricciones sobre cómo se pueden utilizar los datos personales para entrenar modelos. Esto puede limitar la disponibilidad de datos necesarios para desarrollar soluciones efectivas.

4. \textbf{Problemas éticos}
La implementación del aprendizaje automático plantea importantes cuestiones éticas, como el sesgo algorítmico y la equidad en la atención médica. Si los datos utilizados para modelos de entrenamiento reflejan desigualdades existentes, los resultados pueden perpetuar o incluso agravar estas disparidades. Además, la responsabilidad en caso de errores de diagnóstico generados por algoritmos sigue siendo un área gris que necesita ser abordada.

5. Rol del Médico
El papel del médico está evolucionando con la integración del aprendizaje automático en la atención sanitaria. Los profesionales deben adaptarse a trabajar junto a estos sistemas, interpretando sus resultados y tomando decisiones informadas basadas en ellos. Sin embargo, esto requiere capacitación adicional y una mentalidad abierta hacia las nuevas tecnologías, lo que puede ser un desafío para algunos.

Estos desafíos deben ser abordados para maximizar el potencial del aprendizaje automático en la mejora de la atención médica y garantizar que su implementación sea ética, efectiva y accesible para todos.

\section{\textbf{CONCLUSIÓN}}

El machine learning ofrece un enorme potencial para transformar la medicina, desde el pronóstico hasta la personalización de tratamientos. Sin embargo, su implementación enfrenta desafíos significativos como la calidad de los datos, la interpretación de resultados, y cuestiones legales y éticas. A pesar de estos obstáculos, el rol del médico sigue siendo central, ya que el aprendizaje automático debe complementar la experiencia clínica, no reemplazarla. Con el desarrollo adecuado, estas tecnologías podrán mejorar la precisión médica, optimizar recursos y brindar atención más eficiente y personalizada.



\bibliographystyle{alpha}

\bibliography{sample}
Mizutani 
K, Miwa T, Sakamoto Y, Toda M. Application
of deep learning techniques for automated diagnosis of
non-syndromic craniosynostosis using skull. J Craniofac
Surg 2022; 33 (6): 1843-1846.
Mendoz
a CS, Safdar N, Okada K, Myers E, Rogers
GF, Linguraru MG. Personalized assessment of

\end{document}
