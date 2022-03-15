
**القفز من أعلى لأسفل**: [انظر في الداخل](https://scratch.mit.edu/projects/660148605/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/660148605/?autostart=false" frameborder="0"></iframe>
</div>

يعمل هذا الرمز البرمجي على جهاز كمبيوتر مع لوحة مفاتيح وجهاز محمول بشاشة تعمل باللمس.

**كائن الشخصية:**

```blocks3
when I receive [إبدأ v] // الشروع بالبث بعد الاعداد
forever // مناسب مع لوحة مفاتيح وهاتف جوال
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // تكبر أثناء القفز
end
repeat [7]
move [5] steps
change size by [-3] // تصغر عند السقوط
end
end
end
```

