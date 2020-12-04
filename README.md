<!DOCTYPE html>
<html>
    <body>
        <h1>Hello!</h1>
        <input id="a">
        <button id="add">+</button>
        <button id="sub">-</button>
        <button id="mul">*</button>
        <input id="b">
        =
        <label id="res">0</label>
        <script>
            document.querySelector('#add').addEventListener('click', () => {
                let a = parseInt(document.querySelector('#a').value)
                let b = parseInt(document.querySelector('#b').value)
                
                if (isNaN(a) || isNaN(b)) return alert('숫자를 입력해주세요.')
                
                document.querySelector('#res').innerText = a + b
            })
            document.querySelector('#sub').addEventListener('click', () => {
                let a = parseInt(document.querySelector('#a').value)
                let b = parseInt(document.querySelector('#b').value)
                
                if (isNaN(a) || isNaN(b)) return alert('숫자를 입력해주세요.')
                
                document.querySel
