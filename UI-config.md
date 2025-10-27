<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="./style.css">

## [Sumário](#sumário)

* [Guia de Instalação e Utilização do Ollama no Fedora](./Instalando-e-Utilizando.md)
* [Compatibilidade com GPUs antigas](./Compatibilidade-GPU.md)
* [Configuração com Interface Gráfica de Usuário](#configurando-a-interface-gráfica)

-------------------

# Configurando a Interface Gráfica

## Via Llama.cpp (local server)

Caso esteja utilizando `ollama`, rodar no terminal:

```
$ ollama serve --port 11434 deepseek-r1
```

No exemplo é utilizado o modelo `deepseek-r1`. Enquanto estiver rodando o processo no terminal, é possível acessar a interface local do `llama.cpp` visitando o endereço: 
http://localhost:11434/

## Para uso no VSCodium

Seguir a [documentação](https://readmedium.com/using-ollama-in-your-ide-with-continue-e8cefeeee033) da extensão opensource `continue`.

### Ou

Seguir a [documentação](https://docs.ollama.com/integrations/vscode) do site oficial para integração com o GitHub Copilot.
