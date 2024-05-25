<!-- <p align="center">
    <img width="100" src=".github/assets/banner.png">
</p>
 -->

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Course-28DA77?logo=youtube" alt="DIO - course"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-blue?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a></p>

-------

# Projeto EBOOK Gerado por I.A.s


 > ℹ️ **NOTE:** Este é o repositório desenvolvido durante o curso no qual fui instrutor técnico na plataforma da [DIO](https://dio.me)

 > [Repositório original](https://github.com/felipeAguiarCode/prompts-recipe-to-create-a-ebook)


Projeto com o objetivo de gerar um ebook digital com as facilidades das ferramentas de IA. todos os prompts
seguem abaixo.

<a href="" title="View PDF now"> 📕Clique aqui para ler</a>

## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [Runwayml](https://runwayml.com/)
- [LibreOffice Impress](https://books.libreoffice.org/pt-br/IG70/IG7001-Introdu%C3%A7%C3%A3oaoImpress.html)

## 🧠 Prompts


ChatGPT：

|   Ação   | prompt                                                                                                                                                                                                                                                                         |
| :------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  título  | Crie um título de um ebook sobre o tema de ruby, o ebook é do nicho  de programação e o subnincho é ruby, o título  deve ser curto, e tenha  uma temática do o guia do mochileiro das galáxia, me liste 5 variações de títulos |
| conteúdo | Faça um texto para ebook, com foço em programação iniciante em ruby com exemplos de códigos {Regras} Explique sempre de maneira simples, Deixe o texto enxuto, Sempre traga exemplos de códigos em contexto reais , Sempre deixe um título sugestivo do tópico |


Midjourney：

* MidJourney - Não foi possível usar, mas usei outra solução Runwayml para geração de imagens

Runwayml:

|  Ação  | prompt                                                                                 |
| :----: | -------------------------------------------------------------------------------------- |
| título | draws a ruby stone on the screen of a computer called The Deep Thinker and an illustration as if it had been drawn on the cover of "The Hitchhiker's Guide to the Galaxy" by "Chris Riddell" |


## ✨ Features

- Conteúdo gerado via ChatGPT
- Imagens geradas via Runwayml

## 📚 Materiais

- Imagens utilizadas em `assets`
- ebook gerado durante as aulas em `output`

## 🛠️ Instruções de execução

Utilize os prompts acima nas ferramentas sugeridas para gerar o material base e utilize uma ferramenta de edição de documentos como power point, libreoffice , indesign para diagramação.

## 👨‍💻 Expert
<!-- 
<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/37452836?v=4"
    />
    <p>&nbsp&nbsp&nbspFelipe Aguiar<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/felipeAguiarCode">
    GitHub</a>&nbsp;|&nbsp;
    <a href="www.linkedin.com/in/
felipe-exe">LinkedIn</a>
&nbsp;|&nbsp;
    <a href="https://www.instagram.com/felipeaguiar.exe/">
    Instagram</a>
&nbsp;|&nbsp;</p>
</p>
<br/><br/>
<p> -->

---

## Build pdf

```bash
$ soffice --headless --convert-to pdf --outdir output ebook.odp
```

# Contribuindo para Rubyista das Galáxias

Obrigado por considerar contribuir para o Rubyista das Galáxias! Este eBook é um esforço colaborativo e todas as contribuições são bem-vindas, sejam elas pequenas correções de erros, melhorias no conteúdo ou novos recursos.

## Como Contribuir

1. **Fork** o projeto.
2. Crie uma nova **branch** (`git checkout -b feature/nova-contribuicao`).
3. Faça **commit** de suas alterações (`git commit -am 'Adicionar nova contribuição'`).
4. Faça um **push** para a branch (`git push origin feature/nova-contribuicao`).
5. Envie uma **Pull Request**.

Por favor, leia nosso [Guia de Contribuição](link_para_o_guia_de_contribuição) para obter mais detalhes sobre como contribuir para este projeto.

## Ajuda Adicional

Se você tiver alguma dúvida ou precisar de ajuda adicional, sinta-se à vontade para abrir uma issue ou entrar em contato com [Dayan Freitas](https://github.com/Dayanfreitas).

## Agradecimentos

Agradecemos a você por contribuir para tornar este eBook ainda melhor!

Créditos e inspiração por [Felipe Aguiar](https://github.com/felipeAguiarCode)