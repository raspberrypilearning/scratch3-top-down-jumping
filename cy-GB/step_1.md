
**Neidio o'r brig i lawr**: [Gweld tu mewn](https://scratch.mit.edu/projects/525300970/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/525300970/?autostart=false" frameborder="0"></iframe>
</div>

Mae'r cod yma yn gweithio ar gyfrifiadur gyda bysellfwrdd a dyfais symudol gyda sgrin gyffwrdd.

**Corlun cymeriad:**

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
