# HTML: Linguagem de marcação padrão para criar páginas da Web

## Basics:

HTML significa ***Hyper Text Markup Language***, é a linguagem de marcação padrão para criar páginas da Web que descreve a estrutura de uma página da Web numa série de elementos ele informa ao navegador como exibir o conteúdo.

> Os elementos HTML rotulam partes do conteúdo como "isso é um título", "isso é um parágrafo", "isso é um link", etc.

### Exemplo:

    <!DOCTYPE html>
    <html>
    <head>
    <title>Titulo da pagina - aba </title>
    </head>
    <body>

    <h1>Titulo da pagina - webpage</h1>
    <p>Paragrafo 1</p>

    </body>
    </html>)

> Onde:

    <!DOCTYPE html> 
Define que este documento é um documento HTML5

    <html> 
É o elemento raiz de uma página HTML

    <head> 
Contém meta-informações sobre a página HTML (Coisas que o user não vê)

    <title>
Especifica um título para a página HTML (que é mostrado na barra de título do navegador ou na guia da página)

    <body> 
Define o corpo do documento e é um recipiente para todo o conteúdo visível, como títulos, parágrafos, imagens, hiperlinks, tabelas, listas, etc.

    <h1>
Define um título grande
    
    <p>
Define um parágrafo

## Links e Imagens:

-Os ***links*** HTML são definidos com a tag <a>

### Exemplo:
  
    <a href="https://www.google.com" target="_blank">Isso é um link</a>
  
-Onde o atributo target pode ter os seguintes valores:

    _self Padrão. Abre o documento na mesma janela/guia em que foi clicado
    _blank Abre o documento em uma nova janela ou guia
    _parent Abre o documento no quadro pai
    _top - Abre o documento no body todo da janela
  
  
  
-As ***imagens*** HTML são definidas com a tag <img>.
O arquivo de origem (src), texto alternativo (alt), largura e altura são fornecidos como atributos
  
### Exemplo:
  
    <img src="imagemaleatoria.jpg" alt="Descrição da imagem" width="104" height="142">
       
  ## Comentarios em HTML:
  
 Usa-se <!------>
       
### Exemplo:
       
       <!-- Write your comments here -->
       
## Table Cells
       
Cada Table Cell é definida por uma tag <td> e </td>. Uma Table em HTML consiste em células dentro de linhas e colunas.
       
### Exemplo:
       <table>
        <tr>
          <th>Company</th>
          <th>Contact</th>
          <th>Country</th>
        </tr>
        <tr>
          <td>Alfreds Futterkiste</td>
          <td>Maria Anders</td>
          <td>Germany</td>
        </tr>
         <tr>
          <td>Centro comercial Moctezuma</td>
          <td>Francisco Chang</td>
          <td>Mexico</td>
         </tr>
       </table>
       
## Listas
       
Com duas categorias: Ordered Lists (OL) e Unordered Lists (UL)
       
### Exemplo:
       <ul>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
       </ul>
       
## Classes e Id's
       
O atributo de classe é usado para especificar uma classe para um elemento HTML. Vários elementos HTML podem compartilhar a mesma classe. <br>
O atributo id é usado para especificar um id exclusivo para um elemento HTML. Você não pode ter mais de um elemento com o mesmo id em um documento HTML.
       
### Exemplo:
       
    <div id ou class="city">
     <h2>London</h2>
     <p>London is the capital of England.</p>
    </div>

  ## Estilos dentro do HTML:
  
- ***style*** para estilizar elementos HTML
- ***background-color*** pra mudar a cor de fundo
- ***color*** pra mudar a cor do texto
- ***font-family*** pra escolher fontes
- ***font-size*** pra alterar tamanho da fonte
- ***text-align*** pra alinhar texto
  
### Exemplo:
    <h1 style="text-align:center;">Centered Heading</h1>
  
## Formatação de fontes dentro do HTML:

     <b> Texto em negrito
       
     <strong> Texto importante
       
     <i> Texto em itálico
       
     <em> Texto enfatizado
       
     <mark> Texto marcado
       
     <small> Texto menor
       
     <del> Texto excluído
       
     <ins> Texto inserido
       
     <sub> Texto subscrito
       
     <sup> Texto sobrescrito
       
## Css dentro do HTML
       
CSS é usado para estilo e pode ser adicionado a documentos HTML de 3 maneiras:

    Inline - usando o atributo style dentro de elementos HTML
    Internal - usando um elemento <style> na seção <head>
    External - usando um elemento <link> para vincular a um arquivo CSS externo
       
### Exemplos:
       
Inline:
       
      <h1 style="color:blue;">A Blue Heading</h1>
       
Internal:
       
      <style>
        body {background-color: powderblue;}
        h1   {color: blue;}
        p    {color: red;}
      </style>
       
External: Um estilo externo é usada para definir o estilo de muitas páginas HTML
       
        <head>
          <link rel="stylesheet" href="styles.css">
        </head>
         
## JavaScript dentro do HTML

JavaScript makes HTML pages more dynamic and interactive.
E assim como o CSS pode ser adicionado internamente e externamente (em outro documento).
         
         ###Exemplos:
         
         <script>
            document.getElementById("demo").innerHTML = "Hello JavaScript!";
         </script>
         
ou
         
         <script type="text/javascript" src="scripts.js"></script>
         
         
         
         
       

       
       
  
  
  

  





    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
