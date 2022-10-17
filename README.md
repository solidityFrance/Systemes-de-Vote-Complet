# Systemes-de-Vote-Complet

à lire svp:
Vote.sol version du code complet avec commentaires.
Voting.sol version du code sans les commentaires.



Projet demandé et réalisé:
L'administrateur du vote enregistre une liste blanche d'électeurs identifiés par leur adresse Ethereum.
L'administrateur du vote commence la session d'enregistrement de la proposition.
Les électeurs inscrits sont autorisés à enregistrer leurs propositions pendant que la session d'enregistrement est active.
L'administrateur de vote met fin à la session d'enregistrement des propositions.
L'administrateur du vote commence la session de vote.
Les électeurs inscrits votent pour leur proposition préférée.
L'administrateur du vote met fin à la session de vote.
L'administrateur du vote comptabilise les votes.
Tout le monde peut vérifier les derniers détails de la proposition gagnante.

Ajout au projet initial:
L'administrateur peut désinscrire un voter.
L'administrateur peut refuser une proposition.
L'administrateur peut relancer une session de vote.
Ajout d'une sauvegarde automatique des résultats de chaque session.
Consultation des résultats des sessions précédentes.
Possibilité de conserver les voters d'une session à l'autre.
Optimisation des indexs en uint16.
Optimisation de non-affectation des variables.
En cas d'égalité : la priorité sera donnée automatiquement à la proposition la plus ancienne.
Le vote blanc, pour chaque session, est ajouté automatiquement.
  
