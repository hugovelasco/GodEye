Este projeto tem como objetivo criar uma aplicacao capaz de, após percorrer os perfis do facebook, capturar informações de pessoas com base no seu perfil público. Após ter feito o perfilamento, você será capaz de trazer informações da pessoa após o reconhecimento facial. 

## Requisitos
Para o funcionamento da aplicação, é necessário instalar os seguintes módulos através do PIP
- selenium
- BeautifulSoup
- configparser
- sqlite3

## Support
Looking for help? Check out the instructions for getting support.


# Como utilizar
### 1. CapturaProfile
Este modulo é responsável por capturar perfis para os próximos módulos

```console
$ cd CaptureProfile
```
```console
$ python3 CapturaProfile.py
```

Após a execucao deste módulo, o arquivo do sqlite tera uma tabela com 2 campos preenchidos: nome e link. Dessa forma, os outros módulos irão analisar e capturar as informações 


### 2. CapturePhotos
Este modulo é responsável por capturar as fotos do perfil da pessoa, encontros os rostos e salvar apenas os rostos em pastas separadas

```console
$ cd CapturePhotos
```
```console
$ python3 CapturePhotos.py
```

Após a execucao deste módulo, será criada uma pasta para cada perfil. E cada pasta irá conter os rostos encontrados no respectivo perfil