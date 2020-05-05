# Entity Extractor

## Intalação

[Conda](https://docs.conda.io/projects/conda/en/latest/index.html)

## Criar novo ambiente no conda e intalar pacotes necessários
```bash
conda create -n <env> python==3.7

conda activate <env>

pip install -r requirements.txt

pip install omni.nlp --extra-index-url http://techadmin:omni2019%40pypi@repo.oppuz.com:8080/ --trusted-host repo.oppuz.com
```

## Adicionar novo ambiente do conda como kernel do jupyter
```bash
python -m ipykernel install --user --name=<env>
```

## Baixar dataset  e diretorio de models do drive

[Dataset](https://drive.google.com/drive/u/2/folders/19J8P3CQHoeBpWlyOV4JhsTMjse7odh6h)

[Models Embbeding](https://drive.google.com/drive/u/2/folders/1eps7_tLfC91lOE8HX3ynStU47ekGYzUh)

## Iniciar execução de Notebooks

```bash
jupyter notebook
```

Executar notebook 'Extract_data_from_dump' para separar dataset do dump geral

Executar notebook 'Seq2Class_entity_extractor' para treinar o modelo extrator de entidades

## Remover ambiente no conda
```bash
conda env remove --name AmbienteTeste
```