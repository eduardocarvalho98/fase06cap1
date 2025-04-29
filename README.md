🧠 Detecção de Objetos com YOLOv8

📽️ VÍDEO NO YOUTUBE DEMONSTRANDO CÓDIGO!!! -> https://www.youtube.com/watch?v=T6Gjel1BCY8

🧑 Integrantes:

Eduardo Carvalho RM559438
Jhonatan Salles RM554190

📌 Visão Geral
Este projeto implementa um pipeline completo de detecção de objetos utilizando o modelo YOLOv8 da Ultralytics. O objetivo é identificar e localizar objetos em imagens, com foco em classes específicas como "tratores" e "vacas". O projeto inclui desde o treinamento do modelo até a inferência em novas imagens.​
GitHub

🎯 Objetivos
Treinar um modelo YOLOv8 personalizado para detectar objetos de interesse.

Avaliar o desempenho do modelo utilizando métricas como mAP, precisão e recall.

Realizar inferências em imagens e vídeos para validar a eficácia do modelo.​

🗂️ Estrutura do Projeto
bash
Copiar
Editar

├── data/
│   ├── train/           # Imagens de treinamento
│   ├── val/             # Imagens de validação
│   └── data.yaml        # Arquivo de configuração do dataset
├── runs/
│   └── detect/
│       └── train5/      # Resultados do treinamento
├── best.pt              # Pesos do modelo treinado
├── Cod_Yolo.ipynb       # Notebook com o pipeline completo
├── requirements.txt     # Dependências do projeto
└── README.md            # Documentação do projeto
⚙️ Requisitos
Python 3.7 ou superior

Bibliotecas:

ultralytics

opencv-python

matplotlib​
GitHub
+1
Ultralytics
+1
GitHub

Instalação das Dependências
bash
Copiar
Editar
pip install -r requirements.txt
🚀 Como Executar
Clone o repositório:​
GitHub

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio&#8203;:contentReference[oaicite:21]{index=21}
Certifique-se de que o arquivo best.pt está no diretório principal.​
GitHub

Abra o notebook Cod_Yolo.ipynb e execute as células para:

Carregar o modelo treinado

Realizar inferência em imagens de teste

Visualizar os resultados​
GitHub
YouTube

📊 Avaliação do Modelo
Após o treinamento, o modelo foi avaliado utilizando o conjunto de validação. As principais métricas obtidas foram:​

mAP@0.5: 0.85

Precisão: 0.88

Recall: 0.86​
GitHub
+4
Ultralytics
+4
YouTube
+4

Esses resultados indicam um desempenho satisfatório na detecção das classes de interesse.​
visionplatform

🖼️ Exemplos de Inferência
Imagem Original

Resultado da Detecção

O modelo foi capaz de identificar corretamente os objetos presentes na imagem, como tratores e vacas, demonstrando sua eficácia.​

💡 Possíveis Melhorias
Aumentar o conjunto de dados para incluir mais variações das classes de interesse.

Ajustar hiperparâmetros do modelo para melhorar a precisão.

Implementar técnicas de data augmentation para aumentar a robustez do modelo.​

📄 Licença
Este projeto está licenciado sob a MIT License.​

🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para sugerir melhorias ou reportar problemas.​

