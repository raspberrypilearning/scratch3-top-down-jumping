
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Este código funciona em um computador com teclado e em um dispositivo móvel com tela sensível ao toque.

**Ator de Personagem:**

```blocks3
when I receive [start v] // broadcast start after setup
forever // keyboard and mobile friendly
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // get bigger while jumping up
end
repeat [7]
move [5] steps
change size by [-3] // get smaller while falling down
end
end
end
```
