
O script ran_analysis.R tem 5 passos descritos no projeto do curso.

1 - guarda a url em uma variável chamada url

2 - com download.file, salva os arquivos em um diretório chamado CleaneingData, com nome de Dataset.zip

3 - com zip.file.extract, extrai os arquivos nesse diretório

4 - atribui os arquivos: X_train.txt a tmp1 e X_test.txt a tmp2

4.1 - junta tmp1 e tmp2 em __X__ com rbind()

5 - atribui os arquivos: subject_train.txt a tmp1 e subject_test.txt a tmp2

5.1 - junta tmp1 e tmp2 em __S__ com rbind()

6 - atribui os arquivos: y_train.txt a tmp1 e y_test.txt a tmp2

6.1 - junta tmp1 e tmp2 em __Y__ com rbind()

7 - guarda features.txt na variável fetures

8 - usa cbind para megear S, Y, X e gerar o arquivo: merged_clean_data.txt

9 - gera o arquivo data_set_with_the_averages.txt

Variáveis

    tmp1, tmp2, X, Y, S,features, indices_of_good_features, activities, cleaned, result, tmp

