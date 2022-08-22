
**上から見下ろす視点でのジャンプ**: [中を見る](https://scratch.mit.edu/projects/525300970/editor){:target="_ blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/525300970/?autostart=false" frameborder="0"></iframe>
</div>

このコードは、キーボードのあるコンピューターでもタッチスクリーンのあるモバイルデバイスでも動きます。

**キャラクタースプライト:**

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
