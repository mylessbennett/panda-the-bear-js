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
bio_info = document.querySelectorAll('.bio-info-item');
bio_info_list = document.querySelector('.bio-info');
for (let i = 0; i < bio_info.length; i++) {
  bio_info_list.removeChild(bio_info[i]);
};
----------------------------------------------------------------------------