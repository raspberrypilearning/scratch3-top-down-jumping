
**Op en neer springen**: [Bekijk van binnen](https://scratch.mit.edu/projects/687926602/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/687926602/?autostart=false" frameborder="0"></iframe>
</div>

Deze code werkt op een computer met een toetsenbord en een mobiel apparaat met een touchscreen.

**Personage-sprite:**

```blocks3
when I receive [start v] // na ontvangst van start
forever // geschikt voor toetsenbord en mobiel
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // groter worden tijdens het springen
end
repeat [7]
move [5] steps
change size by [-3] // kleiner worden tijdens naar beneden vallen
end
end
end
```
