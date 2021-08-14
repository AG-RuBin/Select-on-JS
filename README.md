# Select on JS (EN)

Creating a simple select function on JavaScript language.

#### HTML

```
    <select name="" id="mySelect" onchange="funSel()">
        <option value="">Apple</option>
        <option value="">Orange</option>
        <option value="">Pineapple</option>
        <option value="">Banana</option>
    </select>
```

#### JavaScript

```
function funSel() {
    var sel = document.getElementById('mySelect').selectedIndex;
    var options = document.getElementById('mySelect').options;
    alert('Выбрана опция ' +options[sel].text);
}
```

# Выборка на JS (RU)

Создание простой функции выборки на языке JavaScript.

#### HTML

```
    <select name="" id="mySelect" onchange="funSel()">
        <option value="">Apple</option>
        <option value="">Orange</option>
        <option value="">Pineapple</option>
        <option value="">Banana</option>
    </select>
```

#### JavaScript

```
function funSel() {
    var sel = document.getElementById('mySelect').selectedIndex;
    var options = document.getElementById('mySelect').options;
    alert('Выбрана опция ' +options[sel].text);
}
```