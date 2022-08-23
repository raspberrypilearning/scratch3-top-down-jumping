
**上から見下ろす視点でのジャンプ**: [中を見る](https://scratch.mit.edu/projects/724133913/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/724133913/?autostart=false" frameborder="0"></iframe>
</div>

このコードは、キーボードのあるコンピューターでもタッチスクリーンのあるモバイルデバイスでも動きます。

**キャラクタースプライト:**

```blocks3
when I receive [開始 v] // 設定が終わったらメッセージを送る
forever // キーボードでもﾓﾊﾞｲﾙデバイスでも動く
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // 飛び上がるときは、だんだん大きくなる
end
repeat [7]
move [5] steps
change size by [-3] // 落ちていくときは、だんだん小さくなる
end
end
end
```
