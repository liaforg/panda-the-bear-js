(1)
var image = document.querySelector('.profile-image');
image.src = "https://placebear.com/400/400";

(1)
var skyImage = document.querySelector('#left-image img');
image.src = " http://bitmakerlabs.github.io/panda-the-bear-js/index.html";

(2)
var title = document.querySelector('h1');
title.innerText = "Lia";

(3)
var employment = document.querySelector('#employment h3');
employment.innerText = "Something else";

(4)
var bodyColour = document.querySelector('body');
bodyColour.style.backgroundColor = "blue";

(5)
var highlight = document.getElementsByClassName('highlight');
$(".highlight").css ('color' , 'red');

(6)
var font = document.querySelector('h1');
font.style.fontFamily = "monospace";

(7)
var roundIcon = document.querySelectorAll('.action-icon-bg');
roundIcon.forEach(function(item) { item.style.backgroundColor = 'blue' })

(8)
var textInput = document.querySelectorAll('input[placeholder = "Name"]');
textInput[0].placeholder = "Identify Yourself"

(9)
var textArea = document.querySelectorAll('textarea[placeholder = "Message"]');
textArea[0].placeholder = "State your business"

(10)
var nameField = document.querySelector('input[type = "text"]');
nameField.value = "your nemesis";

(11)
var emailField = document.querySelector('input[type = "email"]');
emailField.value = "koalathebear@gmail.com"

(12)
var submitButton = document.querySelector('input[type = "submit"]');
submitButton.value = "En garde";

(13)
var submitButton = document.querySelector('input[type = "submit"]');
submitButton.disabled = "Disabled!"

(14)
document.querySelector('form').reset();
