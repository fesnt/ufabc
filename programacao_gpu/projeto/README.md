g++ -std=c++11 -pthread ppm.cpp ppm_05.cpp 

LA NO CUDA
nvcc -x cu ppm.cpp ppm_05.cpp -std=c++11

COPIAR TODOS OS ARQUIVOS DA PASTA ATUAL

scp * felipe.santos92@vision.ufabc.edu.br:/home/felipe.santos92/projeto/