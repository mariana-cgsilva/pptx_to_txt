# pptx_to_txt
Transform a powerpoint file into text

# PowerPoint to Text Extractor

Este projeto contém um script em Python que converte o conteúdo de um arquivo PowerPoint (.pptx) em um arquivo de texto (.txt). É útil para extrair o texto de apresentações para análise, revisão ou outros propósitos.

## Como funciona

O script usa a biblioteca `python-pptx` para ler o arquivo PowerPoint e extrai o texto de cada slide. O texto extraído é então salvo em um novo arquivo de texto.

## Pré-requisitos

Antes de executar o script, certifique-se de ter instalado o Python e a biblioteca `python-pptx`. Você pode instalar a biblioteca `python-pptx` usando o `pip`:

```
pip install python-pptx
```

## Uso

1. **Atualize o caminho do arquivo**:
   Modifique o caminho do arquivo PowerPoint (`ppt`) e o caminho do arquivo de texto de saída (`file`) para corresponder aos locais dos seus arquivos no seu sistema.

2. **Execute o script**:
   Execute o script em um ambiente Python.

## Estrutura do Projeto

```
/
├── README.md
└── extract_ppt_text.py
```

- `README.md`: Este arquivo de documentação.
- `extract_ppt_text.py`: O script Python que realiza a extração do texto.

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
