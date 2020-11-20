# Trabalho-3-algoritmos-Computa-o-Gráfica

Nomes: João Vítor Dall'Agnol e Bruno Saldanha

Exitem tres principais métodos na hora de treinar uma IA atravez do OPENCV. São eles o opencv_annotation, opencv_createsamples e o opencv_traincascade:
  
opencv_annotation:
	  É uma ferramenta para geração de um arquivo de marcação. Ela é feita através de uma janela com a imagem onde devemos fazer a marcação manual do objeto que desejamos conhecer. 
  Quanto mais imagens forem marcadas, mais nossa IA será bem treinada.

opencv_createsamples:
	Usamos esse método através de um comando para criar amostras para o treinamento com as imagens negativas e positivas.

opencv_traincascade:
	  É um método que usamos através de um comando único de prompt para realizar o treinamento da nossa IA, 
  quanto maior as amostras e a quantidade de negativas e positivas maior também será o processo de treinamento. 
  Após o treinamento será gerado o arquivo cascade.xml que podemos utilizar para a detecção.
