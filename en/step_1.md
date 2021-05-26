
**Top-down jumping**: [See inside](https://scratch.mit.edu/projects/525300970/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/525300970/?autostart=false" frameborder="0"></iframe>
</div>

This code works on a computer with a keyboard and a mobile device with a touchscreen.

**Character sprite:**

```blocks3
when I receive [start v]
forever
if <<key (space v) pressed?> or <mouse down?>> then // keyboard and mobile friendly
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
