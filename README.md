# Currículo — Guilherme Kenji Naka

Currículo desenvolvido em HTML e CSS como projeto de aprendizagem em desenvolvimento web. Apresenta resumo profissional, formação acadêmica, experiências profissionais, competências, cursos e certificados.

## Recursos

- Layout responsivo para computadores e celulares.
- Menu com links para as seções do currículo.
- Experiências profissionais ordenadas da mais recente para a mais antiga.
- Logos das instituições e empresas.
- Card da formação IBM Full Stack Software Developer, com progresso de **1/15 cursos concluídos**.
- Miniatura clicável do certificado de Introduction to Software Engineering.
- Estilos específicos para impressão em A4.
- Versão alternativa com telefone e e-mail censurados.

## Estrutura do projeto

```text
.
├── index.html
├── index-publico.html
├── style.css
├── assets/
│   ├── franq-logo.png
│   └── ibm-introduction-software-engineering.jpeg
└── README.md
```

| Arquivo | Descrição |
| --- | --- |
| `index.html` | Currículo completo, com telefone e e-mail. |
| `index-publico.html` | Cópia com telefone e e-mail censurados. |
| `style.css` | Estilos compartilhados pelas duas versões, incluindo responsividade e impressão. |
| `assets/` | Logo da Franq e imagem do certificado IBM usados nas páginas. |

## Como abrir

1. Baixe ou clone o projeto.
2. Abra `index.html` no navegador para visualizar a versão completa, ou `index-publico.html` para visualizar a versão com os contatos censurados.

O projeto não precisa de instalação de dependências, compilação ou servidor. Mantenha os arquivos HTML, o `style.css` e a pasta `assets` na mesma estrutura.

Alguns logos são carregados de sites externos e precisam de conexão com a internet. Os links de cursos e de validação dos certificados também levam a páginas externas.

## Como editar

- **Conteúdo:** altere os textos e links nos arquivos HTML.
- **Visual:** edite `style.css`; as alterações se aplicam às duas versões.
- **Imagens:** adicione os arquivos à pasta `assets` e atualize o atributo `src` da imagem no HTML.
- **Progresso IBM:** atualize o contador `1/15`, o texto de conclusão e o valor do elemento `<progress>` nos dois arquivos HTML.

As duas versões do conteúdo são independentes. Ao atualizar formação, experiências ou certificados, faça a mesma alteração em ambos os arquivos, preservando a censura dos contatos em `index-publico.html`.

## Imprimir ou salvar em PDF

Abra a versão desejada no navegador e pressione `Ctrl + P`. Selecione papel A4 e escolha a impressora ou a opção de salvar como PDF. Confira a prévia antes de concluir, pois a paginação pode variar conforme o navegador e as configurações de impressão.

## Compartilhamento

Para compartilhar a versão com os contatos censurados, envie `index-publico.html` junto com `style.css` e a pasta `assets`. Essa versão mantém o nome, a trajetória profissional e os certificados visíveis.

O arquivo `index.html` contém os contatos completos. Publicar a pasta inteira em um repositório ou site público também disponibiliza esse arquivo, mesmo que a página principal seja a versão censurada.

## Tecnologias

- HTML5
- CSS3

## Autor

Guilherme Kenji Naka — estudante de Ciências Econômicas.

[Repositório do currículo](https://github.com/guinaka-jpg/curriculo-guilherme-naka)
