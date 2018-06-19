## Issue Name

<input type="text" placeholder="My Super Very Long Issue Title" id="input">

<button
onclick="document.getElementById('input').value =
document.getElementById('input').value.toLowerCase().replace(/[^a-z\d\s]/g, '').trim().replace(/\s/g,'-');return false;">
Convert
</button>

### Example Usage
Given the following issue name:

`# TODO: remove type ignore when mypy supports numpy #261`

It will be converted to the following:

`todo-remove-type-ignore-when-mypy-supports-numpy-261`
