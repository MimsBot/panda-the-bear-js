Part 1
Question 1

// get the profile image first
const profileImage = document.querySelector('.profile-image');
// change its src property
profileImage.src = "http://placebacon.net/400/400";

Question 2

const photographyImage = document.querySelector('.photography');
photographyImage.src = "https://picsum.photos/325/225/?image=8";

Question 3

const mainHeading = document.querySelector('h1.highlight');
mainHeading.innerText = "Mimsey";

Question 4

const employmentHeading = document.querySelector('#employment .info-title');
employmentHeading.innerHTML = '<i class="icon-suitcase"></i> &nbsp; Experience';

Question 5

document.body.style.background = 'grey';

Question 6

const highlightElements = document.querySelectorAll('.highlight');
highlightElements.forEach((element) => element.style.color = 'teal');

Question 7

const h1 = document.querySelector('h1');
h1.style.fontFamily = 'monospace';

Question 8

const sideBarIcons = document.querySelectorAll('.action-icon-bg');
sideBarIcons.forEach((icon) => icon.style.backgroundColor = "teal");

Question 9

const nameInput = document.querySelector('input#name');
nameInput.placeholder = 'identify yourself';

Question 10

const messageInput = document.querySelector('textarea');
messageInput.placeholder = 'state your business';

Question 11

const nameInput = document.querySelector('input#name');
nameInput.value = 'your nemesis';

Question 12

const emailInput = document.querySelector('input#email');
emailInput.value = 'koalathebear@gmail.com';

Question 13

const submitInput = document.querySelector('input#submit');
submitInput.value = 'En garde!';

Question 14

const submitInput = document.querySelector('input#submit');
submitInput.disabled = true;

Question 15

const sideBar = document.querySelector('aside');
const bioInfo = document.querySelector('.bio-info');
sideBar.removeChild(bioInfo);