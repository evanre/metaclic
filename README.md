# udata-js

##  demo
http://depthfrance.github.io/udata-js/exemple.html

## utilisation

       <script>window.jQuery || document.write("<script src='//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.0/jquery.min.js'><\/script>")</script>

        <!-- chargement feuille de style bootstrap -->
        <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.6/css/bootstrap.css">
        <!-- chargement feuille de style font-awesome -->
        <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.5.0/css/font-awesome.min.css">

        <div
          class="uData-data"
          data-organizations="534fffb3a3a7292c64a78129,551959f6c751df6682057c91,534fffb9a3a7292c64a7814f,558bef88c751df1fd9a453b9,55896c18c751df5864a453b9,558bf578c751df2f9ea453ea,534fff4ea3a7292c64a77cab"
          data-organization="551959f6c751df6682057c91"
          data-q="eau"
          data-page_size="5">
        </div>

paramètres:
  - data-organizations: ID des organisations proposées dans le menu déroulant
  - data-organization: ID de l'organisation selectionnée (optionnel)
  - data-q: recherche initiale (optionnel)
  - data-page_size: nombre de résultat par page (optionnel)
  - data-sort: tri des résulats, valeurs possibles ['title','created','last_modified','followers','reuses',false] si false le menu est masqué (optionnel, default: title)
  - data-sharelink: boolean si true, affiche le lien de partage (optionnel, default: false)

l'ensemble des paramètres de l'API uData [GET /datasets/](https://www.data.gouv.fr/fr/apidoc/#!/datasets/list_datasets) sont utilisatables

ex: data-tag='transport'

