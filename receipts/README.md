# Desafio 02: Recibos de Pagamento

## Modelo utilizado

Foi usado o modelo pré-treinado LayoutLMv2 proposto por Yang Xu, Yiheng Xu, Tengchao Lv, Lei Cui, Furu Wei, Guoxin Wang, Yijuan Lu, Dinei Florencio, Cha Zhang, Wanxiang Che, Min Zhang e Lidong Zhou, que foi treinado para extração de informações de documentos digitalizados, classificação de imagens de documentos e resposta visual de perguntas. O modelo foi importado da Biblioteca Transformers, que fornece o modelo citado de forma fácil, além de várias ferramentas para ajustar o conjunto de dados.  
Mais informações em [https://huggingface.co/docs/transformers/model_doc/layoutlmv2](https://huggingface.co/docs/transformers/model_doc/layoutlmv2)

## Preparando e rodando o modelo

- Os dados originais estão disponívéis publicamente na tarefa 3 do [desafio SROIE](https://rrc.cvc.uab.es/?ch=13&com=tasks);
- Para facilitar, os arquivos de treino devem ser renomeados no formato ```input(x).jpg``` e ```output(x).txt```;
- Os arquivos já renomeados podem ser baixados [nesse link](https://drive.google.com/file/d/1fnClh5sEa--jWS1GkEYHvN5hpjER_ysQ/view?usp=sharing);
- Os arquivos devem ser colocados em uma pasta do drive, e o endereço dessa pasta deve ser colocado na variável ```root_path```, na primeira célula do [notebook](./DesafioMostQI.ipynb).
