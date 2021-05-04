
**Top-down jumping**: [See inside](https://scratch.mit.edu/projects/525300970/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/525300970/?autostart=false" frameborder="0"></iframe>
</div>

This code works on a computer with a keyboard and a mobile device with a touchscreen.

**Stage:**

```blocks3
when stage clicked // Works on a tablet
broadcast (jump v)
```

**Character sprite:**

```blocks3
when flag clicked // setup
point in direction [90] // Or a different direction
go to x: [-200] y: [0]
set size to [50] % // choose a normal size
```

```blocks3
when [space v] key pressed // choose a key
broadcast (jump v)
```

```blocks3
when I receive [jump v] // jump
if <(size) = [50]> then // avoid double jumping
start sound (Drum Boing v) // add a sound
repeat [10] // jump up
move [5] steps
change size by [3]
end
repeat [10] // come back down
move [5] steps
change size by [-3]
end
set size to [50] % // make sure they are back to normal size
end
```

