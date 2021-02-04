# workflow

[ref issue \#21](https://github.com/openfab-lab/rtfm/issues/21)

**Need:** `Login banque, Login ZOHO, Access TeamDrive/OF-Compta, Access OpenfabNAS, *€-Rigueur-€*`

## Accounting workflow

Ce qu'on appelle par là, c'est la routine mensuelle de mettre à jour les comptes, encoder les nouveaux membres, les factures  d'achats, de ventes et payer ce qu'on doit.

Pour être certain de ne pas oublier un document par ci ou une facture par là, voici une liste des tâches à suivre pour concidérer que la mise à jours des comptes est faite et bien faite.

### TODOLIST

* [ ] **SALES \(ventes\)**

  * [ ] [vérifier les consommation **laser**](https://github.com/openfab-lab/rtfm/tree/6a59e9ed584417da711331da37e1d10734853c2c/Tools/Tools_lasersaur_Book.md)**saur**, **LittleSebastian** \(mini laser\), **cnc** et **PrusaMini,** puis encoder et envoyer les factures adhoc 📑 [_create invoice_](zoho_sales.md)
  * [ ] valider les **factures en attente** à envoyer aux membres, et aux clients si des factures récurrentes ont été créées en "draft"

  ![image](https://user-images.githubusercontent.com/12049360/54280296-6a75e400-4597-11e9-8d99-2055785496ca.png)

  * [ ] Au besoin, encoder les **nouveaux clients/membres**.   
  * [ ] Enregistrer les **factures récurrentes** pour les inscriptions à l'asbl et les cotisations mensuelles 

* [ ] **PuuuuurCHASES \(achats\)**
  * [ ] **Collecter** les tickets et factures \(achats par bancontact, factures, achats en ligne amazon, Aliexpress, etc... \)
  * [ ] **Scanner** les docs papiers, les ajouter à la farde rouge "Achat 2019" et tout réunir sur le NAS dans `//compta/factureIN`
  * [ ] Encoder les achats déjà payé comme **Expenses \(dépenses\)**, avec les justificatifs en pièce jointe.
  * [ ] Encoder les achats à payer comme **Bills \(factures\)**, principalement des factures d'internet, douane, assurance, smartbe, etc... ainsi que note de frais staff. 
* [ ] Payer les **Bills** \(factures\)  Aller sur le compte en ligne, et rechercher les transactions mentionnées "Open et Overdue"
* [ ] Télécharger **les extraits**   

  📑 [_import statement_](zoho_statement.md)

* [ ] **Catégoriser** les mouvements = match entre encodage et mouvement bancaire.
* [ ] vérifier les factures envoyées et **activer les emails de rappels**

-&gt; wootwoot, party hard

### Remarques, astuces et récompenses

~~cheat-sheet du code de la TODOLIST, copypasta de ceci dans l'issue de la tâche,~~

#### Attention:

Cette méthode manuelle est dépréciée.   
Un template spécifique est prévu lors de la création d'une nouvelle issue dans le repo [/devis-et-facturation/issues](https://github.com/openfab-lab/devis-et-facturation/issues)

![newIssueTemplate](https://user-images.githubusercontent.com/12049360/67000753-b3b38680-f0d8-11e9-8b6d-15e30a35e881.png)

```text
- [ ] **SALES**
  - [ ] vérifier le carnet laser, cnc et PrusaMini
  - [ ] valider les factures en attente
  - [ ] encoder les nouveaux clients/membres   
  - [ ] encoder les factures récurrentes pour inscription asbl et membership

- [ ] **PuuuuurCHASES**
  - [ ] Collecter les tickets et factures (tickets, factures, ne pas oublier achats en ligne amazon, Aliexpress, etc... )
  - [ ] Scanner les docs papiers et les ranger
  - [ ] Encoder les achats déjà payé comme **Expenses**
  - [ ] Encoder les achats à payer comme **Bills**

- [ ] Payer les **Bills**  

- [ ] Télécharger les extraits  

- [ ] Catégoriser les mouvements

- [ ] Envoyer les emails de rappel
```

