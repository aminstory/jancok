<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Random Password Generator In Javascript</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.2/css/all.min.css">
<style>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #9b415c;
  height: 100vh;
}

.password-generator {
  padding: 40px;
  background-color: #6f2f42;
  color: white;
  font-size: 20px;
  font-family: sans-serif;
}

.password-generator div {
  display: flex;
  justify-content: space-between;
  margin: 10px 0;
}

.password {
  min-width: 280px;
  background-color: #431c27;
  color: rgb(199, 199, 199);
}

.password p {
  padding: 6px 10px;
}

.password i {
  background-color: rgba(0, 0, 0, 0.575);
  padding: 6px 10px;
}

.password-generator button {
  width: 100%;
  border: none;
  color: rgba(255, 255, 255, 0.699);
  background-color: #2c131a;
  padding: 10px;
}</style>

<body>
  <div class="container">
    <div class="password-generator">
      <h2>Password Generator</h2>
      <div class="password">
        <p id="passwordBox"></p><i class="far fa-clipboard" onclick="copyPassword()"></i></i>
      </div>
      <div>
        <label for="length">Length</label>
        <input type="number" id="length" min="6" max="20" value="6">
      </div>
      <div>
        <label for="symbol">Include Symbol</label>
        <input type="checkbox" id="symbol" checked>
      </div>
      <div>
        <label for="number">Include Number</label>
        <input type="checkbox" id="number" checked>
      </div>
      <div>
        <label for="lowerCase">Include lowerCase</label>
        <input type="checkbox" id="lowerCase" checked>
      </div>
      <div>
        <label for="upperCase">Include upperCase</label>
        <input type="checkbox" id="upperCase" checked>
      </div>
      <button onclick="createPassword()">Get Random Password</button>
    </div>
  </div>
<script>const keys = {
  upperCase: "ABCDEFGHIJKLMNOPQRSTUVWXYZ",
  lowerCase: "abcdefghijklmnopqrstuvwxyz",
  number: "0123456789",
  symbol: "!@#$%^&*()_+~\`|}{[]:;?><,./-="
}
const getKey = [
  function upperCase() {
    return keys.upperCase[Math.floor(Math.random() * keys.upperCase.length)];
  },
  function lowerCase() {
    return keys.lowerCase[Math.floor(Math.random() * keys.lowerCase.length)];
  },
  function number() {
    return keys.number[Math.floor(Math.random() * keys.number.length)];
  },
  function symbol() {
    return keys.symbol[Math.floor(Math.random() * keys.symbol.length)];
  }
];

function createPassword() {
  const upper = document.getElementById("upperCase").checked;
  const lower = document.getElementById("lowerCase").checked;
  const number = document.getElementById("number").checked;
  const symbol = document.getElementById("symbol").checked;
  if (upper + lower + number + symbol === 0) {
    alert("Please check atleast one box!");
    return;
  }
  const passwordBox = document.getElementById("passwordBox");
  const length = document.getElementById("length");
  let password = "";
  while (length.value > password.length) {
    let keyToAdd = getKey[Math.floor(Math.random() * getKey.length)];
    let isChecked = document.getElementById(keyToAdd.name).checked;
    if (isChecked) {
      password += keyToAdd();
    }
  }
  passwordBox.innerHTML = password;
}
function copyPassword() {
  const textarea = document.createElement("textarea");
  const password = document.getElementById("passwordBox").innerText;
  if (!password) { return; }
  textarea.value = password;
  document.body.appendChild(textarea);
  textarea.select();
  document.execCommand("copy");
  textarea.remove();
  alert("Password copied to clipboard");
}</script>

</html>
