# Catálogo

Fotos e dados públicos dos produtos da loja, usados para cadastrar e atualizar anúncios no Bling.

## Estrutura

```
produtos/
  <SKU>/
    produto.json   dados do anúncio (nome, preço, medidas, destaques)
    01.jpg         foto de capa
    02.jpg ...     demais fotos, na ordem do anúncio
```

## Links das imagens

Cada foto fica disponível pela CDN do jsDelivr:

```
https://cdn.jsdelivr.net/gh/Salomaov1/catalogo@main/produtos/<SKU>/01.jpg
```

## Regra

Este repositório é público. Aqui entra só o que já aparece no anúncio.
Custo, fornecedor, margem e dados de clientes ficam no Bling.
