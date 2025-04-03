
**

## Données des Villes Marocaines avec leurs Quartiers et Coordonnées Géospatiales


**🌍 Description**

Ce projet contient un fichier JSON regroupant les villes marocaines avec leurs quartiers ainsi que leurs données géospatiales (latitude et longitude). Ces informations peuvent être utiles pour des applications de cartographie, d'analyse géospatiale ou de navigation.

⚠️ Note : Certaines villes peuvent avoir des quartiers manquants. N'hésitez pas à compléter les données et à envoyer une pull request pour améliorer le projet !

**📂 Contenu du fichier JSON**

Chaque ville est représentée sous la forme d'un objet avec les attributs suivants :

    {
      "city": "Nom de la ville",
      "Neighborhood":[
       {
            "Neighborhood": "Nom de quartier",
            "City": "Nom de la ville ",
            "Lat": "Lat",
            "Lon": Long"
          },
      ]
    }

Exemple :

    "City": "Agadir",
        "Neighborhoods": [
          {
            "Neighborhood": "Afoulki",
            "City": "Agadir",
            "Lat": "30.4300493",
            "Lon": "-9.5557854"
          },
          {
            "Neighborhood": "Agadir Oufella",
            "City": "Agadir",
            "Lat": "30.4244851",
            "Lon": "-9.6114672"
          }
          ]

**🔧 Utilisation**

Vous pouvez utiliser ce fichier JSON dans vos projets en le chargeant et en l'exploitant avec des langages comme JavaScript, Python, ou toute autre technologie supportant le format JSON.



> **Exemple d'utilisation en JavaScript :**


    fetch('chemin/vers/le/fichier.json')
      .then(response => response.json())
      .then(data => console.log(data));

**🛠 Améliorations futures**

Ajout de plus de villes et de quartiers pour améliorer la précision des données.

Intégration d'autres informations utiles (population, superficie,Taux de criminalité, etc.).



**👥 Auteur**

Ce projet a été réalisé par Anas chamkhi .

Si vous avez des suggestions ou des questions, n'hésitez pas à ouvrir une issue ou à proposer une pull request ! 🚀



