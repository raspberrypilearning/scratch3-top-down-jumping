
**Saut de haut en bas** : [Voir à l'intérieur](https://scratch.mit.edu/projects/672835074/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/672835074/?autostart=false" frameborder="0"></iframe>
</div>

Ce code fonctionne sur un ordinateur avec un clavier et un appareil mobile avec un écran tactile.

**Sprite personnage :**

```blocks3
when I receive [démarrer v] // envoyer à tous démarrer après la configuration
forever // compatible clavier et mobile
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // devenir plus grand quand elle saute vers le haut
end
repeat [7]
move [5] steps
change size by [-3] // devenir plus petite quand elle tombre vers le bas
end
end
end
```

