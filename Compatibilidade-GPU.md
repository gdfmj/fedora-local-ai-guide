<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="./style.css">

## [Sumário](#sumário)

* [Guia de Instalação e Utilização do Ollama no Fedora](./Instalando-e-Utilizando.md)
* [Compatibilidade com GPUs antigas](#verificando-a-compatibilidade-da-gpu)
* [Configuração com Interface Gráfica de Usuário](./UI-config.md)

-------------------

# Verificando a compatibilidade da GPU

[A lista de todas as GPUs compatíveis oficialmente.](https://github.com/ollama/ollama/blob/main/docs/gpu.md)

## Para GPU RX580

[Preparar o docker.](https://docs.docker.com/engine/install/fedora/)

[Instalar em um docker.](https://hub.docker.com/r/mnccouk/ollama-gpu-rx580)

### OU

Instalar o `ramalama` via `dnf`, que utiliza os mesmos comandos do `ollama` e instala os mesmos modelos LLM com compatibilidade para GPUs mais antigas:

```
$ sudo dnf install ramalama
```