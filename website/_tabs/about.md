---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

# Saint-Pierre et Miquelon - Demains numériques

Le contenu de ce site est publié sous Licence Creative Commons Attribution (CC BY 4.0)

  <p>
    {{ '©' }}
    <time>{{ 'now' | date: '%Y' }}</time>
    <a href="{{ site.social.links[0] }}">{{ site.social.name }}</a>.
    {% if site.data.locales[include.lang].copyright.brief %}
      <span
        data-bs-toggle="tooltip"
        data-bs-placement="top"
        title="{{ site.data.locales[include.lang].copyright.verbose }}"
      >
        {{- site.data.locales[include.lang].copyright.brief -}}
      </span>
    {% endif %}
  </p>

## Le contenu de ce site revêt-il un caractère politique ?

Bien que ce site s'efforce d'opérer de manière indépendante de tout mouvement politique, son objectif ultime est de construire un matériel informatif et persuasif susceptible de susciter l'intérêt et le soutien en faveur de certaines idées ou causes. Nous tenons à souligner que notre engagement en faveur de l'indépendance politique ne signifie pas que nous ne cherchons pas à influencer positivement les débats publics. Notre intention est de fournir des informations éclairées et de promouvoir des discussions constructives, dans le but de contribuer au processus démocratique et de sensibiliser à certaines questions. Nous reconnaissons la responsabilité qui découle de notre capacité à influencer l'opinion publique et nous nous engageons à présenter des arguments éthiques, équilibrés et fondés sur des faits.

## Appel à la Participation

En tant que créateurs de contenu, nous aspirons à façonner un espace inclusif et diversifié où différentes perspectives peuvent converger. Votre engagement et votre contribution active sont essentiels pour enrichir le dialogue et élargir la portée des idées discutées ici

## Avis de non-responsabilité de l'équipe éditoriale

En tant que responsables techniques de la mise en œuvre de ce site, il est crucial de souligner que le contenu exprime nos opinions personnelles et ne prétend pas être une source exhaustive ou impartiale d'information. Les points de vue partagés ici sont les nôtres et susceptibles d'évoluer avec le temps. Les informations présentées sont basées sur nos expériences, connaissances et perspectives, sans intention d'offenser ou de diffamer toute personne, organisation ou groupe.

Malgré nos efforts pour synthétiser les contributions et maintenir l'exactitude des informations, nous ne pouvons garantir l'absence d'erreurs, d'omissions ou d'informations périmées. Les lecteurs sont encouragés à consulter d'autres sources et à exercer leur propre discernement. Nous portons la responsabilité du matériel éditorial, mais cela n'exclut pas la possibilité d'erreurs involontaires. De plus, ce site peut contenir des liens vers des sites tiers dont le contenu et les politiques de confidentialité ne relèvent pas de notre contrôle. Vous acceptez également que les auteurs du site déclinent toute responsabilité sur les commentaires publiés par les utilisateurs. L'utilisation des opinions, conseils et informations affichées, y compris les commentaires, est à la discrétion du visiteur.


Hébergé sur GitHub Pages : [code source](https://github.com/damienlaine/spm)