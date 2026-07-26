shared repository for python group project

1. Nettoyer les noms des colonnes
   - Supprimer les espaces
   - Uniformiser les noms des colonnes

2. Nettoyer les colonnes texte
   - Supprimer les espaces inutiles
   - Supprimer les guillemets "
   - Uniformiser majuscules/minuscules
   - Corriger les valeurs différentes qui représentent la même catégorie

3. Nettoyer les IDs
   - Supprimer les guillemets
   - Supprimer les espaces
   - Vérifier les doublons
   - Garder le type texte (object)

4. Nettoyer Date et Time
   - Convertir Date en datetime
   - Vérifier le format Time
   - Créer une colonne DateTime si nécessaire

5. Convertir les colonnes numériques
   - Booking Value
   - Ride Distance
   - Avg VTAT
   - Avg CTAT
   - Driver Ratings
   - Customer Rating

6. Gérer les valeurs manquantes (Missing Values)
   - Identifier les NaN
   - Supprimer ou remplacer selon le contexte

7. Supprimer les doublons
   - Détecter les lignes répétées
   - Supprimer les duplications

8. Vérifier les valeurs aberrantes (Outliers)
   - Distances négatives
   - Valeurs de réservation négatives
   - Notes hors intervalle (0-5)
   - Temps impossibles

9. Nettoyer les catégories
   - Vehicle Type
   - Booking Status
   - Payment Method
   - Locations
   - Uniformiser les noms

10. Nettoyer les statuts de réservation
    - Completed
    - Cancelled
    - Incomplete
    - No Driver Found

11. Nettoyer les colonnes de raisons
    - Reason for cancelling by Customer
    - Driver Cancellation Reason
    - Incomplete Rides Reason
    - Remplacer les valeurs vides si nécessaire

12. Vérifier les types de données
    - datetime pour les dates
    - float/int pour les nombres
    - object pour les textes et IDs

13. Réinitialiser l'index après modifications

14. Sauvegarder le dataset nettoyé
    - Exporter en CSV
