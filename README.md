<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projet final</title>
    
</head>
<body>

    <p id="date"></p>

    <script>
        function afficherDate() {
            const dateActuelle = new Date();
            const options = {
                weekday: 'long', year: 'numeric', month: 'long', day: 'numeric',
                hour: '2-digit', minute: '2-digit', second: '2-digit'
            };
            document.getElementById('date').innerHTML = dateActuelle.toLocaleDateString('fr-FR', options);
        }

        // Appelle la fonction afficherDate toutes les secondes (1000 millisecondes)
        setInterval(afficherDate, 1000);
    </script>
    <!-- /Main Header -->

        <!-- Lower Header -->
        <div id="lower-header">

          <div class="container">

              <div id="menu-button">
                  <div>
                      <span></span>
                      <span></span>
                      <span></span>
                  </div>
                  <span>Menu</span>
              </div>

              <ul id="navigation">

                  <!-- Home -->
                  <li class="home-button current-menu-item">

                      <a href="/ci/"><i class="icons icon-home"></i></a>

                  </li>
                  <!-- /Home -->

                  <!-- Pages -->
                  <li class="">

                      <span>Accueil</span>

                      <ul>

                          <li><a href="C:\Users\MENA\Desktop\projet final\A propos.html">A propos</li>
                            <!-- <a href="C:\Users\MENA\Desktop\projet final\A propos.html"target="_blank">A propos</a> -->

                          <li><a href="C:\Users\MENA\Desktop\projet final\projets.html">Projets</a></li>
                          <!-- <a href="C:\Users\MENA\Desktop\projet final\projets.html"target="_blank">Mes projets</a> -->
                          <li><a href="/ci/direction/mission">Hobbies</a></li>
                          <li><a href="/ci/direction/mission">sport</a></li>

                      </ul>

                  </li>
                  <!-- /Pages -->

                  <!-- Events -->
                  <li class="">

                      <span>Compétences</span>

                      <ul>

                          <li><a href="C:\Users\MENA\Desktop\projet final\compétences.html"target="_blank">compétences</a></li>
                          

                      </ul>

                  </li>
                  <!-- /Events -->

                  <!-- Media -->
                  <li class="">

                      <span>Contact</span>

                      <ul>

                          <li>
                              <a href="C:\Users\MENA\Desktop\projet final\formualire.html"target="_blank">formulaire</a>
                          </li>

                        
                  <!-- /Media -->

              </ul>

          </div>

      </div>
      <!-- /Lower Header -->
