BairesDev - Machine Learning Practitioner

Projeto de criação de uma base de dados e treinamento da rede YOLO .

Versões utilizadas:
Python = 3.10.4
Cuda = https://developer.nvidia.com/cuda-downloads?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_local

cuDNN = https://developer.nvidia.com/cudnn-downloads?target_os=Windows&target_arch=x86_64&target_version=Agnostic&cuda_version=12

opencv = https://github.com/opencv/opencv/releases/download/4.10.0/opencv-4.10.0-windows.exe

Imagens baixadas = https://storage.googleapis.com/openimages/web/index.html

Classes utilizadas para treinar a rede yolov3 são: Oven, Rose e Bench. Cada uma delas escolhidas aleatóriamente pelo botão "Random class" do open images dataset v7.
As imagens utilizadas para treino estão na pasta "data/obj" junto com as annotations necessárias para a yolov3 ler a imagem.

Toolkit utilizado para fazer o dataset = https://github.com/theAIGuysCode/OIDv4_ToolKit
