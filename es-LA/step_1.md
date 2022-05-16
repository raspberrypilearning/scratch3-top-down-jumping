
**Brincar**: [Ve al código](https://scratch.mit.edu/projects/691156978/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/691156978/?autostart=false" frameborder="0"></iframe>
</div>

Este código funciona en una computadora con teclado y en un dispositivo móvil con pantalla táctil.

**Sprite del personaje:**

```blocks3
when I receive [inicio v] // iniciar código después de la configuración
forever // compatible con el teclado y dispositivos móviles
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // incrementar el tamaño al subir
end
repeat [7]
move [5] steps
change size by [-3] // reducir el tamaño al bajar
end
end
end
```
