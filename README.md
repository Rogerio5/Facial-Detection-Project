# Facial-Detection-Project

# 🧠 Projeto de Detecção Facial com WEB CAM

## 🚀 Reconhecimento de rostos em imagens via Google Colab

![Capa do Projeto - Detecção Facial](Exemplo-Rogerio.png)

---

## 🏅 Badges

- 📦 Tamanho do repositório / Repository Size:  
  ![GitHub repo size](https://img.shields.io/repo-size/Rogerio5/Facial-Detection-Project)

- 📄 Licença do projeto / Project License:  
  ![GitHub license](https://img.shields.io/github/license/Rogerio5/Facial-Detection-Project)

---

## 📋 Índice / Table of Contents

- [Descrição / Description](#descrição--description)  
- [Status / Status](#status--status)  
- [Funcionalidades / Features](#funcionalidades--features)  
- [Execução / Execution](#execução--execution)  
- [Tecnologias / Technologies](#tecnologias--technologies)  
- [Desenvolvedor / Developer](#desenvolvedor--developer)  
- [Licença / License](#licença--license)  
- [Conclusão / Conclusion](#conclusão--conclusion)  

---

## 📖 Descrição / Description

**PT:**  
Este projeto demonstra como aplicar técnicas avançadas de visão computacional para realizar reconhecimento facial em imagens e webcam, utilizando o ambiente interativo do Google Colab. A aplicação permite:

📁 Carregar imagens locais ou via upload no Colab

🧠 Detectar rostos com o detector MTCNN

🔍 Extrair características faciais com Keras-FaceNet

🧪 Classificar rostos com SVM ou realizar verificação facial

📸 Capturar imagens diretamente da webcam (opcional)

🖼️ Exibir comparações lado a lado entre imagem original e imagem detectada

💾 Salvar imagens processadas com bounding boxes e nomes identificados

**EN:**  
This project demonstrates how to apply advanced computer vision techniques to perform facial recognition using images and webcam input, all within the interactive environment of Google Colab. The application allows you to:

📁 Upload training and test images directly in Colab

🧠 Detect faces using the MTCNN face detector

🔍 Extract facial features with Keras-FaceNet

🧪 Classify faces using SVM or perform facial verification

📸 Capture images from the webcam (optional)

🖼️ Display side-by-side comparisons of original and detected images

💾 Save processed images with bounding boxes and identified names

---

## 🚧 Status / Status

- ✅ Detecção facial funcional com Haar Cascade  
- ✅ Visualização interativa com Matplotlib  
- ✅ Upload e captura de imagens no Colab  
- ✅ Pronto para expansão com DNN ou MTCNN

---

## ⚙️ Funcionalidades / Features

| 🧩 Funcionalidade (PT)                      | 💡 Description (EN)                          |
|--------------------------------------------|----------------------------------------------|
| 🖼 Upload de imagem no Colab                | 🖼 Upload image via Colab interface           |
| 📷 Captura via webcam (opcional)           | 📷 Webcam capture (optional)                 |
| 🧠 Detecção com Haar Cascade                | 🧠 Face detection using Haar Cascade         |
| 🖼 Comparações lado a lado                  | 🖼 Side-by-side visual comparisons            |
| 💾 Salvamento de imagem detectada          | 💾 Save processed image with bounding boxes  |

---

## 🚀 Execução / Execution

**PT:**  
Para executar o projeto no Colab:

1. Faça upload da imagem ou use a webcam  
2. Carregue o classificador Haar Cascade  
3. Aplique a detecção facial com `cv2.CascadeClassifier`  
4. Exiba os resultados com `matplotlib`  
5. Salve a imagem detectada com `cv2.imwrite`

**EN:**  
To run the project on Colab:

1. Upload an image or use webcam  
2. Load Haar Cascade classifier  
3. Apply face detection using `cv2.CascadeClassifier`  
4. Display results using `matplotlib`  
5. Save detected image using `cv2.imwrite`

---

## 🌐 Acesso / Access

- [Repositório GitHub / GitHub Repository](https://github.com/Rogerio5/Facial-Detection-Project)

---

## 🧰 Tecnologias / Technologies

<p>
  <img align="left" alt="Python" title="Python" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg"/>
  <img align="left" alt="OpenCV" title="OpenCV" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/3/32/OpenCV_Logo_with_text_svg_version.svg"/>
  <img align="left" alt="Google Colab" title="Google Colab" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg"/>
  <img align="left" alt="Matplotlib" title="Matplotlib" width="30px" style="padding-right: 10px;" src="https://matplotlib.org/_static/images/logo2.svg"/>
  <img align="left" alt="Keras-FaceNet" title="Keras-FaceNet" width="30px" style="padding-right: 10px;" src="https://avatars.githubusercontent.com/u/34455048?s=200&v=4"/>
  <img align="left" alt="Scikit-learn" title="Scikit-learn" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg"/>
  <img align="left" alt="TensorFlow" title="TensorFlow" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Tensorflow_logo.svg"/>
</p>

<br clear="all"/>

---

## 👨‍💻 Desenvolvedor / Developer

- [Rogerio](https://github.com/Rogerio5)   

---

## 📜 Licença / License

Este projeto está sob licença MIT. Para mais detalhes, veja o arquivo `LICENSE`.  
This project is under the MIT license. For more details, see the `LICENSE` file.

---

## 🏁 Conclusão / Conclusion

**PT:**  
Este projeto é uma introdução prática à detecção facial com OpenCV, ideal para quem deseja explorar visão computacional de forma acessível. A estrutura modular permite expandir para múltiplas faces, detecção em vídeo e integração com redes neurais.

**EN:**  
This project is a practical introduction to face detection with OpenCV, ideal for those exploring computer vision in an accessible way. Its modular structure allows expansion to multi-face detection, video processing, and neural network integration.
