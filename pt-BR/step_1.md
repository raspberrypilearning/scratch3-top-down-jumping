
**Salto de cima para baixo**: [Veja o interior](https://scratch.mit.edu/projects/525300970/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/525300970/?autostart=false" frameborder="0"></iframe>
</div>

Este código funciona em um computador com teclado e em um dispositivo móvel com tela sensível ao toque.

**Ator de Personagem:**

```blocks3
when I receive [início v] // início da transmissão após configuração
forever // compatível com teclado e dispositivos móveis
if <<key (espaço v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // fique maior enquanto pula
end
repeat [7]
move [5] steps
change size by [-3] // ficar menor ao cair
end
end
end
```
