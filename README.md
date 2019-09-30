# Conda

# Exemplos de uso das funcionalidade do Conda

Criando ambiente conda:

```
conda create -n teste
```

Listando ambientes criados:
```
conda-env list
```

Acessando o ambiente conda:
```
source activate teste
```

Quando estiver em um ambiente é possível executar comandos relacionados aos pacotes:

Buscar Pacote
```
conda search numpy
```

Instalar Pacote
```
conda install numpy
conda install pandas
```

Listar Pacotes instalados
```
conda list
```

Remover um pacote
```
conda remove pandas
```

exportar um ambiente
```
conda-env export -n teste33 -f t33.yml
```

importar um ambiente
```
conda-env create -f teste33.yml
```

Buscando um pacote usando pip:
```
pip search pyparty
```

Instalando um pacote usando pip:
```
pip install pyparty
```

Uma busca por pacotes usando conda pode retornar mais de uma versão de pacote
```
conda search python
```

Comando para instalar uma versão específica da biblioteca
```
conda install python=3.6.3
```

Comando para instalar pacote definindo prioridade de busca de canal
```
conda search scipy --channel conda-forge
```

Instalando pacote de um canal específico
```
conda install python --channel intel
```
