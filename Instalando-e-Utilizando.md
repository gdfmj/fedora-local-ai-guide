<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="./style.css">

## [Sumário](#sumário)

* [Guia de Instalação e Utilização do Ollama no Fedora](#guia-de-instalação-e-utilização-de-ia-com-ollama-no-fedora)
* [Compatibilidade com GPUs antigas](./Compatibilidade-GPU.md)
* [Configuração com Interface Gráfica de Usuário](./UI-config.md)

-------------------

# Guia de Instalação e Utilização de IA com [Ollama](https://ollama.com/) no Fedora

Para o uso de IA localmente utilizando Fedora, é recomendada a instalação do Ollama.

    ATENÇÃO!! Apenas a partir do Fedora 42 que está disponível a instalação com suporte nativo do Ollama.

## Instalação via DNF

No terminal, rodar as atualizações disponíveis dos pacotes instalados e em seguida instalar o Ollama:

```
$ sudo dnf upgrade -y && sudo dnf install -y ollama
```

Com essa instalação já é possível usar o ollama diretamente pelo terminal.

## Comandos Básicos

Utilizaremos o `deepseek-r1` como exemplo de modelo a ser baixado e executado.

### Baixar um modelo

Para apenas baixar um modelo, escrever no terminal:

```
$ ollama pull deepseek-r1
```

### Rodar um modelo

Para rodar via terminal um modelo já baixado é só digitar:

```
$ ollama run deepseek-r1
```

Caso o modelo ainda não tenha sido baixado, `ollama` executará um `pull` automáticamente.

### Remover um modelo

Para remover um modelo já instalado:

```
$ ollama remove deepseek-r1
```

### Listar modelos instalados

Para verificar quais os modelos já instalados, rodar no terminal:

```
$ ollama list
```
