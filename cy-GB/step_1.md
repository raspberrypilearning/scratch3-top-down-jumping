
**Neidio o'r brig i lawr**: [Gweld tu mewn](https://scratch.mit.edu/projects/777359803/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/777359803/?autostart=false" frameborder="0"></iframe>
</div>

Mae'r cod yma yn gweithio ar gyfrifiadur gyda bysellfwrdd a dyfais symudol gyda sgrin gyffwrdd.

**Corlun cymeriad:**

```blocks3
when I receive [dechrau v] // darlledu dechrau ar ôl gosod
forever // gwell ar gyfer bysellfwrdd a ffonnau symudol
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // mynd yn fwy wrth neidio i fyny
end
repeat [7]
move [5] steps
change size by [-3] // mynd yn llai wrth syrthio i lawr
end
end
end
```
