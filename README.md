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
