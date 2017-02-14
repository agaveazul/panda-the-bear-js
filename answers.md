1 a. $('.profile-image').attr('src',"https://pbs.twimg.com/profile_images/477576764785307650/IrGfYELW.jpeg")
1 b. $('#left-image img').attr('src',"http://4.bp.blogspot.com/-MGES8sUsmY8/VTaupeajSfI/AAAAAAAAgIc/EgKTUgCsHrU/s1600/a-fcbteamphoto-2015.jpg")

2.('h1.highlight').text('Ricardo')
3.$($('h3.info-title')[1]).text('Football wins')
4.$('#time-travel').parent().remove();
5.$('body').css('background-color', 'blue')
6.$('.highlight').css('color','gray')
7.$('h1').css('font-family','monospace')
8.$('.action-icon-bg').css('background-color','blue')
9.$('#name').attr('placeholder','Identify yourself')
10.$('#message').attr('placeholder','state your business')
11.$('#name').attr('value','your nemesis')
12.$('#email').attr('value','koalathebear@gmail.com')
13.$('#submit').attr('value','En garde!')
14.$('.action-icon-bg').last().attr('disabled',true)
15.$('.bio-info').empty()
16.$('#right-image img').clone().insertAfter('form')
17.for(i=0;i<10;i++) {$('#right-image img').clone().insertAfter('form')}
18.

var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');

leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);

$(listItem).attr('class','bio-info-item')
var rightSpan = document.createElement('span');
var day = new Date
var date = document.createTextNode(day)
rightSpan.appendChild(date)

listItem.append(rightSpan)
$('ul.bio-info').append(listItem)
