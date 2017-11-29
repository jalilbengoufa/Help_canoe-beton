## Help To Update canoe-beton
(without Git commands)

### Mettre à jour votre Fork

- Pour s'assurer que votre repository est à jour, supprimez la et appuyez sur `Fork` dans la repository source 
 
    1. Cliquer sur `Settings`  [Image en aide](https://github.com/jalilbengoufa/Help_canoe-beton/blob/master/1.png)

    2. Supprimer la repository en cliquant sur `Delete this repository` [Image en aide](https://github.com/jalilbengoufa/Help_canoe-beton/blob/master/2.png )
    3. Dans `ClubCedille/canoe-beton`  appuyer sur  `Fork` [Image en aide](https://github.com/jalilbengoufa/Help_canoe-beton/blob/master/3.png)



### Ajouter un membre

 - Il suffit d'ajouter ce code HTML dans la `Section : Team ` du fichier `index.html`
 
    - *Il faut un maximum de 4 memebre entre le tag `<div class="row">`*
    - *Ne pas oublier de changer le path pour la photo*
    
 ```
  <div class="col-xs-6 col-sm-6 col-md-3">
      <div class="wow bounceInUp" data-wow-delay="0.5s">
        <div class="team boxed-grey">
          <div class="inner">
            <h5>Nom du membre</h5>
            <div class="avatar"><img data-src="images/pathDuDossierPhotos.jpg" alt=""
                                     class="img-responsive img-circle"/></div>
            <p class="subtitle">Post</p>
          </div>
        </div>
      </div>
  </div>
 ```
 
 ### Ajouter une compétition
 
 - Ajouter ce code HTML dans la `Section : Competition ` du fichier `index.html`
  ```
  <br>
  <div class="container">
    <div class="row">
      <div class="col-xs-12 col-lg-4">
        <p><b>Type de compétition:</b> à modifier</p>
        <p><b>Lieu de compétition:</b> à modifier</p>
        <p><b>Placement:</b> à modifier</p>
      </div>
      <div class="col-xs-12 col-sm-12 col-lg-8">
      <img data-src="images/pathImageCompetition.png" alt=""
           class="img-responsive "/>
      </div>
    </div>
</div>
  ``` 
  
### Ajouter un sponsor
 - Ajouter ce code HTML dans la `Section : sponsors ` du fichier `index.html`
   - *Il faut que les sponsors soient entre le tag `<div class="row">` pour être sur la même ligne*
  ``` 
  <div class="col-xs-6 col-sm-3 col-md-3">
       <div class="wow bounceInUp" data-wow-delay="0.2s">
         <div class="team boxed-grey">
           <div class="inner">
             <div><img data-src="images/sponsors/image.jpg" alt="" class="img-responsive"/></div>
           </div>
         </div>
       </div>
  </div>
  ``` 


 
   
