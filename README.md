# TFG_EEAE2025_ANEXO-CODIGO
Códigos anexados a la entrega del Trabajo de Fin de Grado "Diseño de un algoritmo de aterrizaje automático por visión artificial para UAV" por Enrique Román García

**Código 1** - UDP_encode.m: Función codificadora del mensaje UDP  
**Código 2** - UDP_decode.m: Función decodificadora del mensaje UDP (Channel_to_single como auxiliar)  
**Código 3** - adim_coeff.m: Modelo de aeronave Cessna-172SP. Derivadas de estabilidad adimensionales 
**Código 4** - geomass_properties.m: Modelo de aronave Cessna-172SP. Propiedades geométricas, de masa e inercia
**Código 5** - dim_coeff.m: Derivadas de estabilidad dimensionales (Cessna-172SP)  
**Código 6** - trim.m: Algoritmo de trimado (Fuente: Stevens)  
**Código 7** - transp.m: Modelo 3-DOF auxiliar para el trimado (Fuente: Stevens)  
**Código 8** - cost.m: Función de coste del algoritmo de trimado  
**Código 9** - init_aircraft.m: Script de arranque que inicializa derivadas y matrices del modelo  
**Código 10** - envelope_sfcn.c: S-function que calcula la envolvente de una señal  
**Código 11** - vars_latdir.m: Prototipado de ganancias (lateral-direccional)  
**Código 12** - vars_long.m: Prototipado de ganancias (lazos longitudinales)  
**Código 13** - getRunwayLines.m: Función para el cálculo de la proyección de líneas de pista
**Código 14** - transformToCamera.m: Función auxiliar para la generación de líneas de pista. Coordenadas en sistema de cámara 
**Código 15** - poseEstimator.m: Función de estimación de posición dados los puntos en pantalla  
**Código 16** - realPose.m: Función de cálculo de posición real  
**Código 17** - yolo_rwy.py: Archivo de configuración del modelo YOLOv8 
**Código 18** - train.py: Script de entrenamiento YOLOv8  
**Código 19** - prepare_lard.py: Preprocesado y split del dataset LARD  
**Código 20** - augment_to_trainval.py: Data augmentation y mezcla train/val  
**Código 21** - export_onnx.py: Exportación del modelo a ONNX  
**Código 22** - BBoxDetector.h: Cabecera del módulo BBoxDetector  
**Código 23** - BBoxDetector.cpp: Implementación del módulo BBoxDetector  
**Código 24** - NoseCameraPlugin.cpp: Plugin de X-Plane que envía imágenes por pipe  
**Código 25** - ImageReceiver.h: Cabecera del módulo ImageReceiver  
**Código 26** - ImageReceiver.cpp: Implementación del módulo ImageReceiver  
**Código 27** - RunwayDetector.h: Cabecera del módulo RunwayDetector   
**Código 28** - RunwayDetector.cpp: Implementación del módulo RunwayDetector  

