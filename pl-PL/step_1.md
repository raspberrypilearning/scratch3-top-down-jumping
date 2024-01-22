
**Skakanie w widoku z góry**: [Zobacz kod](https://scratch.mit.edu/projects/954447779/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/954447779/?autostart=false" frameborder="0"></iframe>
</div>

Kod ten działa na komputerze z klawiaturą oraz urządzeniu mobilnym z ekranem dotykowym.

**Duszek postaci:**

```blocks3
when I receive [start v] // rozpoczęcie animacji po konfiguracji
forever // przyjazny dla klawiatury i urządzeń mobilnych
if <<key (spacja v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // zwiększaj swój rozmiar podczas skakania
end
repeat [7]
move [5] steps
change size by [-3] // zmniejszaj swój rozmiar podczas spadania
end
end
end
```
