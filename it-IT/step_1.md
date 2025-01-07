
**Salti dall'alto**: [Guarda dentro](https://scratch.mit.edu/projects/1117309305/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/1117309305/?autostart=false" frameborder="0"></iframe>
</div>

Questo codice funziona su un computer con una tastiera o su un dispositivo mobile con un touchscreen.

**Sprite del personaggio:**

```blocks3
when I receive [start v] // manda il segnale start dopo la configurazione iniziale
forever // funziona sia con la tastiera che con il touchscreen
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // ingrandisce lo sprite quando salta
end
repeat [7]
move [5] steps
change size by [-3] // rimpicciolisce lo sprite quando ricade a terra
end
end
end
```
