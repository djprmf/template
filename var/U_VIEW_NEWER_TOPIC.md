# U_VIEW_NEWER_TOPIC
* __Type :__ variable d'affichage
* __Utilisable dans :__ [`viewtopic_body`](../tpl/viewtopic_body.md#readme)
* __Utilisation :__

```smarty
{U_VIEW_NEWER_TOPIC}
```

## Description[*](https://fa-tvars.appspot.com/var/U_VIEW_NEWER_TOPIC)
Remplacé par l'URL absolue menant au sujet :

* du même sous-forum
* avec une dernière réponse moins récente que celle du sujet sur lequel on est
* avec le plus petit intervalle entre la dernière réponse et la dernière réponse du sujet sur lequel on est

Si il n'y a pas de sujet suivant ces conditions, en allant à l'adresse une page d'erreur avec `Il n'y a pas de nouveaux sujets dans ce forum` sera affichée.

* __Remplacement en étant sur `/t11-mon-sujet` :__ `/t11n-mon-sujet`

## Utilisations dans les templates

### Version phpBB3
* __[`viewtopic_body`](../tpl/viewtopic_body.md#readme) :__ lignes [`111`](../src/prosilver/viewtopic_body.tpl#L111), [`256`](../src/prosilver/viewtopic_body.tpl#L256)

### Version phpBB2
* __[`viewtopic_body`](../tpl/viewtopic_body.md#readme) :__ lignes [`116`](../src/subsilver/viewtopic_body.tpl#L116), [`287`](../src/subsilver/viewtopic_body.tpl#L287)

### Version PunBB
* __[`viewtopic_body`](../tpl/viewtopic_body.md#readme) :__ lignes [`124`](../src/punbb/viewtopic_body.tpl#L124), [`269`](../src/punbb/viewtopic_body.tpl#L269)

### Version Invision
* __[`viewtopic_body`](../tpl/viewtopic_body.md#readme) :__ lignes [`298`](../src/invision/viewtopic_body.tpl#L298)

