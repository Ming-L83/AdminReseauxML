## Créer une Unité d'Organisation (OU)

1. Ouvrez "Active Directory Users and Computers".
2. Côte gauche, cliquez droit sur le nom du domaine (wilders.lan) et sélectionnez "New" puis "Organizational Unit".
3. Nommez l'Unité d'Organisation (OU) `Wilders_students`.
4. Cliquez sur "OK".

## Créer un Groupe d'utilisateurs

1. Dans "Active Directory Users and Computers", naviguez jusqu'à l'OU `Wilders_students` que vous venez de créer.
2. Cliquez droit sur l'OU `Wilders_students`, puis sélectionnez "New" et "Group".
3. Nommez le groupe `Students`.
4. Sous "Group scope", sélectionnez "Global".
5. Sous "Group type", sélectionnez "Security".
6. Cliquez sur "OK".

## Créer un Utilisateur au sein de ce Groupe

1. Dans l'OU `Wilders_students`, cliquez droit et sélectionnez "New" puis "User".
2. Remplissez les informations suivantes :
    - First name: `Wilder`
    - Last name: `11`
    - User logon name: `wilder`
3. Cliquez sur "Next".
4. Entrez et confirmez le mot de passe pour l'utilisateur.
5. Décochez la case "User must change password at next logon" si vous ne souhaitez pas imposer ce changement.
6. Cliquez sur "Next" puis "Finish" pour créer l'utilisateur.
7. Cliquez droit sur l'utilisateur `Wilder 11` que vous venez de créer et sélectionnez "Add to a group".
8. Entrez `Students` et cliquez sur "Check Names" pour vérifier le nom du groupe.
9. Cliquez sur "OK" pour ajouter l'utilisateur au groupe `Students`.
