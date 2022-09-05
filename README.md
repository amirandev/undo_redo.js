### How to use?

**First of all you should link the undo_redo.js file somewhere on the page:**

`<script  src="undo_redo.js"></script>`

**Than wirite something like this**

```
<div class="undoredoPanel">
    <button id="undo">Undo</button>
    <button id="redo">Redo</button>
</div>
<textarea id="editor" cols="70" rows="8"></textarea>
```

**And add the foloowing code to your javascript**
```
<script>
    new UndoRedo({'editor' : '#editor', 'undo' : '#undo', 'redo' : '#redo'}).start();
</script>
```
