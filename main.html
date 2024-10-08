<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tableau de bord allôs</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="sidebar">
        <ul>
            <li><a href="#" class="active">Tableau de bord</a></li>
            <li><a href="#">Menu allôs</a></li>
            <li><a href="#">Les membres du BDE</a></li>
            <li><a href="staff.html">Staff only</a></li>
        </ul>
    </nav>
    <main>
        <h1>Tableau de bord allôs</h1>
        <div class="titres">
            <br><br>
            Allô - Coloc - Alloyeurs - Statut
        </div>
        <div id="activities-list" class="liste_allos"></div>
    </main>

    <script type="module">
        // Le reste du script JavaScript reste inchangé
        import { db } from './firebase.js';
        import { collection, getDocs } from "https://www.gstatic.com/firebasejs/9.15.0/firebase-firestore.js";

        async function getActivities() {
            const activitiesCol = collection(db, 'activites');
            const activitiesSnapshot = await getDocs(activitiesCol);
            const activitiesList = activitiesSnapshot.docs.map(doc => doc.data());
            return activitiesList;
        }

        function displayActivities(activities) {
            const activitiesListElement = document.getElementById('activities-list');
            activitiesListElement.innerHTML = '';
            activities.forEach(activity => {
                if (activity.statut == "en cours"){
                const activityElement = document.createElement('div');
                activityElement.textContent = `${activity.nom} - ${activity.coloc} - ${activity.alloyeurs} - ${activity.statut}`;
                activitiesListElement.appendChild(activityElement);
            }});
            activities.forEach(activity => {
                if (activity.statut == "en préparation"){
                const activityElement = document.createElement('div');
                activityElement.textContent = `${activity.nom} - ${activity.coloc} - ${activity.alloyeurs} - ${activity.statut}`;
                activitiesListElement.appendChild(activityElement);
            }});
            activities.forEach(activity => {
                if (activity.statut == "en attente"){
                const activityElement = document.createElement('div');
                activityElement.textContent = `${activity.nom} - ${activity.coloc} - ${activity.alloyeurs} - ${activity.statut}`;
                activitiesListElement.appendChild(activityElement);
            }});
        }

        getActivities().then(displayActivities);
    </script>
</body>
</html>
