# HTML Examples of Letters.

The [classic-letter.html](https://github.com/Lifebot-api/html-examples/blob/master/classic-letter.html) template with the variables below will generate a PDF like this one : [classic-letter.pdf](https://github.com/Lifebot-api/html-examples/blob/master/classic-letter.pdf)

```
'variables': {
  'destinataire': {
    'prenom': 'Prenom du destinataire',
    'nom': 'Nom du destinataire',
    'adresse': {
      'voie': 'Numero et rue de l\'adresse',
      'code_postal': 'Code postal',
      'ville': 'Ville'
    }
  },
  'expediteur': {
    'prenom': 'Prenom de l\'expéditeur',
    'nom': 'Nom de l\'expéditeur',
    'signature': 'Signature de l\'expéditeur',
    'adresse': {
      'voie': 'Numero et rue de l\'adresse',
      'code_postal': 'Code postal',
      'ville': 'Ville'
    }
  },
  'fait': {
    'date': '28/06/2017',
    'lieu': 'Paris'
  },
  'objet': 'Présentation Lifebot',
  'contenu': `
Lifebot propose une <b>API d’impression et d’envoi de courriers en ligne</b> flexible et moderne. 
<br/>
<br/>
          Avec celle-ci vous allez pouvoir développer très facilement vos propres applications, en fonction de votre activité.
<br/>
<br/>
          Vous pourrez, par exemple, automatiser l’envoi d’un <b>courrier promotionnel</b> personnalisé lorsque votre client n’aura pas réalisé d’achat sur votre site depuis plus de 2 mois.
<br/>
      Ou bien, si vous préférez vous cantonner aux <b>courriers transactionnels</b>, vous pourrez de la même façon automatiser l’envoi de vos recommandés de relances impayés lorsqu’un délai de paiement aura dépassé 30 jours.
<br/>
<br/>
      Quelque soit votre besoin, vous pourrez très simplement envoyer <b>n’importe quel type de courrier</b>, pour <b>n’importe quel volume</b>, en ligne.
<br/>
<br/>
      <b>Aucun frais d’installation préalables</b>, vous ne payez que le courrier que vous consommez à la fin du mois comprenant une petite commission pour notre service.
<br/>
<br/>
      Notre solution prend <b>2 minutes</b> à intégrer sur votre CRM ou sur votre site web.
      <br/>
      C’est à la portée de n’importe quel développeur, la documentation est accessible sans inscription sur notre site. Avec juste un copier/coller de ce code, vous êtes prêts à envoyer du courrier.
<br/>
<br/>
      Alors rendez-vous sur lifebot.fr.
    `
  }
}
```
