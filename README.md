
# Generación de imágenes con DCGAN y Stable Diffusion

## Descripción

Este proyecto aborda la implementación de modelos generativos mediante técnicas de Deep Learning, utilizando Redes Generativas Adversarias (DCGAN) y modelos de difusión (Stable Diffusion).
El propósito es comprender el funcionamiento de estas arquitecturas mediante la preparación de datos, entrenamiento, generación de imágenes sintéticas y análisis de resultados.

## Objetivos

- Implementar una arquitectura DCGAN utilizando PyTorch.
- Comprender el entrenamiento adversarial entre el generador y el discriminador.
- Aplicar fine-tuning a Stable Diffusion mediante Diffusers y LoRA.
- Analizar los resultados y las limitaciones computacionales de ambos modelos.

## Tecnologías utilizadas

- Python
- Google Colab
- PyTorch
- Torchvision
- Hugging Face
- Diffusers
- Transformers
- PEFT y LoRA
- NumPy
- Matplotlib

## Implementaciones

### 1. DCGAN

Implementación de una red generativa adversarial convolucional para generar imágenes sintéticas de rostros humanos utilizando el dataset LFW.

El notebook incluye:
- Preparación y transformación de imágenes.
- Arquitectura del generador y discriminador.
- Entrenamiento adversarial.
- Visualización de pérdidas.
- Generación de imágenes sintéticas.

### 2. Stable Diffusion con LoRA

Adaptación de un modelo Stable Diffusion preentrenado mediante la técnica LoRA, que permite reducir la cantidad de parámetros entrenables y los recursos computacionales necesarios.

El notebook incluye:
- Carga del modelo preentrenado.
- Preparación del dataset.
- Configuración de LoRA.
- Fine-tuning del modelo.
- Registro de pérdidas.
- Generación de imágenes mediante prompts.

## Ejecución

1. Descargar los notebooks de este repositorio.
2. Abrirlos en Google Colab.
3. Activar un entorno de ejecución con GPU, preferiblemente T4.
4. Instalar las dependencias indicadas.
5. Ejecutar las celdas secuencialmente.

## Resultados

Las implementaciones permitieron experimentar con el entrenamiento adversarial y la adaptación eficiente de modelos de difusión.
Los resultados deben interpretarse considerando las limitaciones de hardware, tamaño del dataset y tiempo de entrenamiento. La aplicación efectiva de los pesos LoRA durante la inferencia requiere una verificación adicional.

## Conclusion

Las GANs y los modelos de difusión representan diferentes enfoques para la generación de imágenes sintéticas. Su implementación permite comprender las ventajas, desafíos y requerimientos computacionales asociados a los modelos generativos.

