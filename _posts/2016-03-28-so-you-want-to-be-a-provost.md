---
title: So you want to be a Provost...
layout: post
---

I heard you want to be a Provost one day.  Maybe you should ...

<i><b><span id="dostuff">(turn javascript on so you can see this)</span></b></i>

Don't like your advice?  Reload this page.

Want to see the whole list?  <a id="all_the_things">Click here</a>

<script>
var things = [
    'Attempt to rip the chain off a sitting monarch\'s neck',
    'Build an anonymous report card system for provosts',
    'Challenge someone to an actual duel',
    'Convince the entire army to scream "Fuck em in the ass"',
    'Do some service.  Maybe.  I\'ve heard it\'s important.',
    'Enjoy fighting',
    'Fight "Ninja Monkey Style"',
    'Fight in Battle of Nations',
    'Frequently use the excuse "Connor says it was OK"',
    'Get a longer sword',
    'Get into Krav Maga',
    'Get smacked upside the head with a mallet.',
    'Have a pirate ship',
    'Have your emails forwarded from a private mailing list',
    'Just keep doing what you\'re doing',
    'Move to Lochmere',
    'Play daggers for shots!',
    'Punch an opponent',
    'Say there is no checklist and then check your list',
    'Screw up your knee',
    'Screw up your shoulder',
    'Show the ferocity of the Atlantian Army on the field by outfitting them all with feather boas.',
    'Start a snarky podcast',
    'Start wearing orange pants',
    'Stop fencing',
    'Take a personal student while a free scholar',
    'Take up crossfit',
    'Tell people to "JFP".',
    'Throw your mask across the field',
    'Use a decapitated baby doll head as a parrying device',
    'Wear a bright gold jerkin',
    'Win everything.  Win some more, and then maybe win a few more things.  Only then think about service.  Maybe.',
];
var thing = things[Math.floor(Math.random() * things.length)];
document.getElementById('dostuff').innerHTML = "&nbsp;&nbsp;&nbsp;" + thing;

function add_all() {
    result = '<ul>';
    for (var i in things) {
        result += '<li>' + things[i] + '</li>';
    }
    result += '</ul>';
    document.getElementById('dostuff').innerHTML = result;
}

$('#all_the_things').click(function() { 
    add_all();
});

</script>

