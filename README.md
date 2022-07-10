# Huffman-Compressor

Compressor de arquivo usando a codificação de Huffman

### Relatório

[Acessar](https://github.com/pauloh-alc/Huffman-Compressor/blob/main/relatorio_huffman_paulo_henrique_494837.pdf)

### Execução do código fonte

1° - Você precisa instalar o gcc com o seguinte comando:

```sh
sudo apt-get install gcc
```
2° - Você pode compilar um código fonte:
```sh
gcc huffman.c -o huffman
```

3° - Execução:

* Formato básico

```sh
./executavel [opcao] [arquivo_1] [arquivo_2]
```

* Para comprimir
```sh
./huffman c arquivo.txt comprimido.bin
```

* Para descomprimir

```sh
 ./huffman d comprimido.bin descomprimido.txt
```

* c, --comprimir: comprime o arquivo de entrada.

* d, --descomprimir: descomprime o arquivo de entrada.

#### License

MIT
