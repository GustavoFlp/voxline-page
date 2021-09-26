## Orgânização das pastas

### **Assim que a pasta for clonada, entre nela e rode o comando `yarn` no seu terminal**

``
$ yarn
``


### **Build e minificação do tailwind :**

Para buildar o tailwind inicial ou buildar as alterações feitas no tailwind.config use o comando abaixo:
<br />
``
$ yarn build:css
``
> Irá criar um arquivo na página css com o nome de tailwind-build.css

Para minificar o tailwind para produção use o comando abaixo:
<br />
``
$ yarn build:cssnano
``
> Irá criar um arquivo na página css com o nome de tailwind-min.css

### **Images :**
> as imagens estão sendo separadas em:  
> * prod = production
> * dev = development

as images da pasta de produção devem sempre está mais otimizadas possíveis para estarem no site.

<br/>

<strong>Alguns serviços que já foram utilizados e validados pela empresa:</strong>

<table>
 <tr>
  <th>Serviço</th>
  <th>Acesso</th>
  <th>Típo</th>
 </tr>
 <tr>
  <th>TinyPNG</th>
  <th><a href="https://tinypng.com/">https://tinypng.com/</a></th>
  <th>Website</th>
 </tr>
 <tr>
  <th>Imagemin</th>
  <th><a href="https://tinypng.com/">https://tinypng.com/</a></th>
  <th>Pacote do NPM</th>
 </tr>
 <tr>
  <th>iloveimg</th>
  <th><a href="https://www.iloveimg.com/pt/comprimir-imagem">https://www.iloveimg.com/pt/comprimir-imagem</a></th>
  <th>Website</th>
 </tr>
</table>