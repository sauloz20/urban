# Urban Line

Protótipo de loja de moda urbana com página inicial, catálogo e seleção de produtos para gerar uma mensagem ao WhatsApp.

## Tecnologias

HTML, CSS e JavaScript no navegador, Bootstrap, Font Awesome e AOS. Imagens e bibliotecas são carregadas de serviços externos.

## Requisitos e execução

Use um navegador moderno e uma conexão à internet para os recursos externos. Com Git e Python 3 instalados:

```sh
git clone https://github.com/sauloz20/urban.git
cd urban
python -m http.server 8000
```

Acesse `http://localhost:8000/`. Também é possível servir a pasta com Apache/XAMPP.

## Estado do projeto

A loja é uma demonstração estática. A seleção monta uma mensagem para o WhatsApp, sem backend, controle de estoque ou processamento de pagamento no repositório. Os números de WhatsApp no código são exemplos e precisam ser revisados antes de uso real. Alguns links da navegação são marcadores.

## Estrutura

```text
index.html    Página inicial
produto.html  Catálogo
style.css     Estilos compartilhados
produto.css   Folha de estilos adicional presente no projeto
```
