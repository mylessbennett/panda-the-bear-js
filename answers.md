PART 1

1.
let profileImage = document.querySelector('.profile-image');
profileImage.src = "https://placebear.com/400/400";
----------------------------------------------------------------------------
2.
let skyPhoto = document.querySelector('.portfolio-image .photography');
skyPhoto.src = "https://picsum.photos/325/225";
----------------------------------------------------------------------------
3.
mainHeading = document.querySelector('h1.highlight');
mainHeading.innerText = 'Myles Bennett';
----------------------------------------------------------------------------
4.
employmentHeader = document.querySelector('#employment h3');
employmentHeader.innerText = 'Work History';
----------------------------------------------------------------------------
5.
document.body.style.color = 'teal';
----------------------------------------------------------------------------
6.
highlightClass = document.querySelectorAll('.highlight');
for (let i = 0; i < highlightClass.length; i++) {
  let item = highlightClass[i];
  item.style.color = 'tomato'; 
}
----------------------------------------------------------------------------
7.
document.querySelector('h1').style.fontFamily = 'monospace';
----------------------------------------------------------------------------
8.
icons = document.querySelectorAll('.action-icon-bg');
for (let i = 0; i < icons.length; i++) {
  let item = icons[i];
  item.style.backgroundColor = 'teal'; 
};
----------------------------------------------------------------------------
9.
document.querySelector('#name').placeholder = "identify yourself";
----------------------------------------------------------------------------
10.
document.querySelector('#message').placeholder = "state your business";
----------------------------------------------------------------------------
11.
document.querySelector('#name').value = "your nemesis";
----------------------------------------------------------------------------
12.
document.querySelector('#email.contact-info').value = "koalathebear@gmail.com";
----------------------------------------------------------------------------
13.
document.querySelector('#submit').value = "En garde!";
----------------------------------------------------------------------------
14.
document.querySelector('#submit').disabled = true;
----------------------------------------------------------------------------
15.
bioInfo = document.querySelectorAll('.bio-info-item');
bioInfoList = document.querySelector('.bio-info');
for (let i = 0; i < bioInfo.length; i++) {
  bioInfoList.removeChild(bioInfo[i]);
};
----------------------------------------------------------------------------

PART 2
----------------------------------------------------------------------------
Removing Elements from the DOM
1.
let timeTravel = document.querySelector('div.bar-default > #time-travel');
parent = timeTravel.parentNode
parent.removeChild(timeTravel);
----------------------------------------------------------------------------
Adding Elements to the DOM
1.
let pikachu = document.querySelector('div#right-image.portfolio-image img');
let pikachu2 = pikachu.cloneNode(true);
let portfolioContainer = document.querySelector('.portfolio-container');
portfolioContainer.appendChild(pikachu2);
----------------------------------------------------------------------------
2.
for (let i = 0; i <=10; i++) {
    pikachu2 = pikachu.cloneNode(true);
    portfolioContainer.appendChild(pikachu2);
};
----------------------------------------------------------------------------
3.
const lisItem = document.createElement('li');
const listItem = document.createElement('li');
const leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
var date = new Date()
date = document.createTextNode(date);
const rightSpan = document.createElement('span');
rightSpan.appendChild(date);
listItem.appendChild(rightSpan);
document.querySelector('ul.bio-info').appendChild(listItem);
----------------------------------------------------------------------------

----------------------------------------------------------------------------

----------------------------------------------------------------------------

----------------------------------------------------------------------------

