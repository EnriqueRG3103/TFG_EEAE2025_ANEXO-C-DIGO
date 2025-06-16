# TFG_EEAE2025_ANEXO-C-DIGO
Códigos anexados a la entrega del Trabajo de Fin de Grado "Diseño de un algoritmo de aterrizaje automático por visión artificial para UAV" por Enrique Román García

**Código 1** - UDP_encode.m: Función codificadora del mensaje UDP  
**Código 2** - UDP_decode.m: Función decodificadora del mensaje UDP (Channel_to_single como auxiliar)  
**Código 3** - hold_last_SFcn.c: S-function en C que mantiene el último valor recibido hasta llegada del siguiente  
**Código 4** -   
**Código 5** - dim_coeff.m: Derivadas de estabilidad dimensionales (Cessna-172SP)  
**Código 6** - trim_algo.m: Algoritmo de trimado (punto de equilibrio)  
**Código 7** - model_3dof.m: Modelo 3-DOF auxiliar para el trimado  
**Código 8** - cost_function.m: Función de coste del algoritmo de trimado  
**Código 9** - init_aircraft.m: Script de arranque que inicializa derivadas y matrices del modelo  
**Código 10** - envelope_sfcn.c: S-function que calcula la envolvente de una señal  
**Código 11** - vars_latdir.m: Prototipado de ganancias (lateral-direccional)  
**Código 12** - vars_long.m: Prototipado de ganancias (lazos longitudinales)  
**Código 13** - diseno_lazo_p.m: Diseño del lazo p mediante Bode/Root-Locus  
**Código 14** - diseno_lazo_phi.m: Diseño del lazo Φ (alabeo) (LQR)  
**Código 15** - diseno_curso.m: Diseño del lazo de rumbo (course-hold)  
**Código 16** - diseno_speed.m: Control de velocidad con compensador Lead  
**Código 17** - config.yaml: Fichero de configuración para train.py  
**Código 18** - train.py: Script de entrenamiento YOLOv8  
**Código 19** - prepare_lard.py: Preprocesado y split del dataset LARD  
**Código 20** - augment_to_trainval.py: Data augmentation y mezcla train/val  
**Código 21** - export_onnx.py: Exportación del modelo a ONNX  
**Código 22** - BBoxDetector.hpp: Cabecera del módulo BBoxDetector  
**Código 23** - BBoxDetector.cpp: Implementación del módulo BBoxDetector  
**Código 24** - NoseCameraPlugin.cpp: Plugin de X-Plane que envía imágenes por pipe  
**Código 25** - ImageReceiver.hpp: Cabecera del módulo ImageReceiver  
**Código 26** - ImageReceiver.cpp: Implementación del módulo ImageReceiver  
**Código 27** - VisionApp.cpp: Ejecutable principal de procesado visual  
**Código 28** - RunwayDetector.cpp: Implementación del módulo RunwayDetector  

Código 27 - VisionApp.cpp: Ejecutable principal de procesado visual
Código 28 - RunwayDetector.cpp: Implementación del módulo RunwayDetector
