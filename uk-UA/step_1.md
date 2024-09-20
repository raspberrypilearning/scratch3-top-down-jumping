
**Стрибки: вид згори**: [Переглянути код](https://scratch.mit.edu/projects/1070653671/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/1070653671/?autostart=false" frameborder="0"></iframe>
</div>

Цей код працює на комп’ютерах з клавіатурою та мобільних пристроях із сенсорним екраном.

**Спрайт персонажа:**

```blocks3
when I receive [старт v] // оповістити за допомогою повідомлення «старт» після налаштування
forever // підходить як для клавіатур, так і для мобільних пристроїв
if <<key (пробіл v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // збільшується, коли стрибає вгору
end
repeat [7]
move [5] steps
change size by [-3] // зменшується, коли опускається
end
end
end
```
