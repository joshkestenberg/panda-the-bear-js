1. $('.profile-image').attr('src', 'http://i2.kym-cdn.com/photos/images/original/000/878/135/4a2.jpg').width(400).height(400);

2. $('#left-image > img').attr('src', 'http://www.redbrick.me/wp-content/uploads/2015/10/noodle-2.jpg').height(225).width(325);

3. var title = $('.highlight')[1];
$(title).text('Noodle The Dude');

4. var suitcase = $('.icon-suitcase');
$('#employment h3').html(suitcase).append('&nbsp; Emboilment');

5. var timeTrav = $('.bar-default')[2];
$(timeTrav).remove();

6. $('body').css('color', 'yellow');

7. $('.highlight').css('color', 'black');

8. $('h1').css('font-family', 'monospace');

9. $('.action-icon-bg').css('background-color','yellow');

10. $('#name').attr('placeholder', 'Identify Yourself');

11. $('#message').attr('placeholder', 'State Your Business');

12. $('#name').attr('value', 'Your Nemesis');

13. $('#email').attr('value', 'koalathebear@gmail.com');

14. $('#submit').attr('value', 'En Garde!');

<!-- bonus -->

1. $('#submit').attr('disabled', 'true');

2. $('.bio-info').empty();

<!-- add elements -->

1. $('#right-image img').clone().appendTo('section');

2. for (var i = 0; i < 10; i++) {$('#right-image img').clone().appendTo('section');

3. var listItem = document.createElement('li')

   var leftSpan = document.createElement('span');
   var lastUpdated = document.createTextNode('Last Updated');

   var rightSpan = document.createElement('span');
   var date = document.createTextNode('2/14/2017');

   listItem.appendChild(leftSpan);
   listItem.appendChild(rightSpan);
   leftSpan.appendChild(lastUpdated);
   rightSpan.appendChild(date);

   var list = document.getElementsByClassName('bio-info');
   list[0].appendChild(listItem);
