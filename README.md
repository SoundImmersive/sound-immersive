SOUND IMMERSIVE — structure de navigation

index.html
  -> pays/
      -> regions/
          -> villes/
              -> types/
                  -> articles/

Flux :
Accueil > Pays > Région > Ville > Type de lieu > Article

Les cartes utilisent les photos déjà présentes dans le projet.
Les pages d'articles existantes ne sont pas modifiées.

Pour ajouter un nouvel article :
1. Ajouter sa page dans /articles/
2. Ajouter une carte dans la page "type" correspondante.
3. S'il s'agit d'une nouvelle ville, créer sa page dans /villes/ et une carte dans la région.
4. Pour une nouvelle région, créer sa page dans /regions/ et l'ajouter au pays.
5. Pour un nouveau pays, créer sa page dans /pays/ et ajouter sa carte à index.html.

IMPORTANT :
- Le dossier d'images reste /image/ comme dans ton projet actuel.
- Les liens vers les articles existants sont conservés.
- Les catégories de type proposées ici sont des exemples basés sur les articles actuels ; tu peux les renommer.
-------------------------------------------------------------------------------------------------
Catégorie	Ce qu’on y met
🌿 Nature	------------------forêt, rivière, campagne, montagne, oiseaux, vent, pluie…
🏛️ Patrimoine	--------------châteaux, églises, monuments, villages historiques, sites remarquables…
🏙️ Ville & rues	------------rues, places, quartiers, circulation, ambiances urbaines…
🛍️ Marchés & commerces -----marchés, halles, boutiques, cafés, commerces…
🚉 Gares & transports	------gares, trains, métros, bus, stations, ports de transport…
🌊 Mer & littoral	----------plages, ports, vagues, falaises, littoral…
⚽ Sport & loisirs	--------terrains, événements sportifs, activités de plein air…
🎭 Culture & événements	----concerts, festivals, spectacles, manifestations culturelles…
🧑‍🤝‍🧑 Vie locale	--------------terrasses, fêtes, rassemblements, scènes de vie quotidienne…
🏭 Industrie & travail -----ateliers, usines, chantiers, activités professionnelles…

--------------------------------------------------------------------------------------------

Chaque photo possède son orientation directement dans le tableau :
DANS ARTICLES
{
  src: "../image/veron1.jpg",
  focus: "center",
  orientation: "right"
}

Donc pour chaque photo, tu renseignes simplement :

front  = devant
back   = derrière
right  = droite
left   = gauche
--------------------------------------------------------------------------


Photos paysage : 3840 × 2160 px, 16:9
Photos verticales : conserver leur format vertical, ne pas les déformer
