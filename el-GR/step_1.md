
**Άλμα πάνω κάτω**: [Δες μέσα](https://scratch.mit.edu/projects/691156641/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/691156641/?autostart=false" frameborder="0"></iframe>
</div>

Αυτός ο κώδικας λειτουργεί σε υπολογιστή με πληκτρολόγιο και κινητή συσκευή με οθόνη αφής.

**Χαρακτήρας:**

```blocks3
when I receive [έναρξη v] // μετάδοση μηνύματος έναρξης μετά τις ρυθμίσεις
forever // φιλικό για πληκτρολόγιο και κινητά
if <<key (space v) pressed?> or <mouse down?>> then 
start sound (Jump v)
repeat [7]
move [5] steps
change size by [3] // μεγαλώνει όσο ανεβαίνει
end
repeat [7]
move [5] steps
change size by [-3] // μικραίνει όσο κατεβαίνει
end
end
end
```
