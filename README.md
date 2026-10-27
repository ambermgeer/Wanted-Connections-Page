
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Carroll Wanted Connections</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
<style>
:root {
  --accent: #8F402C;
  --ink: #000;
  --paper: #F7F3F0;
}
* { box-sizing: border-box; }
body {
  margin: 0;
  padding: 24px 12px;
  color: var(--ink);
  font: 10px/1.65 Montserrat, sans-serif;
}
#wanted { max-width: 900px; margin: auto; }
.page-title, .card-title {
  font-family: 'Dancing Script', cursive;
  color: var(--accent);
  font-weight: 700;
  text-transform: uppercase;
}
.page-title {
  text-align: center;
  font-size: 48px;
  line-height: 1.2;
  margin: 0;
}
.subtitle { text-align: center; margin: 4px 0 20px; }
.filter-label {
  text-align: center;
  color: var(--accent);
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1.5px;
  margin: 14px 0 7px;
}
.filters {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  justify-content: center;
  margin-bottom: 12px;
}
.filter {
  background: transparent;
  border: 1px solid var(--accent);
  color: var(--accent);
  padding: 6px 10px;
  font: 600 9px Montserrat, sans-serif;
  text-transform: uppercase;
  cursor: pointer;
}
.filter:hover, .filter.active {
  background: var(--accent);
  color: white;
}
.grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 14px;
}
.card {
  background: var(--paper);
  border: 1px solid var(--accent);
  padding: 16px;
  display: flex;
  flex-direction: column;
}
.card[hidden] { display: none !important; }
.card-top {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 8px;
  padding-bottom: 9px;
  margin-bottom: 9px;
  border-bottom: 1px solid #8f402c70;
}
.card-title { font-size: 30px; line-height: 1.15; margin: 0; }
.status {
  border: 1px solid #54764c;
  color: #54764c;
  padding: 3px 6px;
  font-weight: 700;
  font-size: 8px;
  letter-spacing: .6px;
  text-transform: uppercase;
  white-space: nowrap;
}
.status.taken { color: var(--accent); border-color: var(--accent); }
p { margin: 4px 0; }
.label { color: var(--accent); font-weight: 700; }
.description { margin: 10px 0; }
.bottom {
  margin-top: auto;
  padding-top: 9px;
  border-top: 1px solid #8f402c60;
}
a { color: var(--accent); text-decoration: none; font-weight: 600; }
a:hover { text-decoration: underline; }
.note { text-align: center; margin-top: 18px; font-size: 9px; }
@media(max-width:650px) {
  .grid { grid-template-columns: 1fr; }
  .page-title { font-size: 42px; }
}
</style>
</head>
<body>
<main id="wanted">

<h1 class="page-title">Wanted Connections</h1>
<p class="subtitle">Browse all wanted connections from the characters of Carroll.</p>

<div class="filter-label">Availability</div>
<div class="filters">
  <button class="filter active" data-group="status" data-value="all">All Connections</button>
  <button class="filter" data-group="status" data-value="open">All Open</button>
  <button class="filter" data-group="status" data-value="taken">All Taken</button>
  <button class="filter" data-group="new" data-value="new">Newly Added</button>
</div>

<div class="filter-label">Connection Type</div>
<div class="filters">
  <button class="filter active" data-group="type" data-value="all">All Types</button>
  <button class="filter" data-group="type" data-value="familial">Familial</button>
  <button class="filter" data-group="type" data-value="romantic">Romantic</button>
  <button class="filter" data-group="type" data-value="ex-romantic">Formerly Romantic</button>
  <button class="filter" data-group="type" data-value="platonic">Platonic</button>
  <button class="filter" data-group="type" data-value="professional">Professional</button>
  <button class="filter" data-group="type" data-value="rivalry">Rivalry</button>
  <button class="filter" data-group="type" data-value="antagonistic">Conflict</button>
  <button class="filter" data-group="type" data-value="other">Other / Mixed</button>
</div>

<section class="grid" id="connection-grid">

<!-- TOMAS ACOSTA DE VISSER -->
<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Siblings</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Tomas Acosta de Visser</a></p>
  <p><span class="label">Name / age:</span> UTP · 25–38</p>
  <p><span class="label">Suggested FCs:</span> Latinx POC, mixed heritage, or any FC if adopted</p>
  <p class="description">The Acosta de Visser family is big and rowdy. Tomas grew up with two older siblings and two younger ones, and all the children helped at the family bakery. As they got older, some pursued their own ambitions while others continued helping at the bakery or stayed close to Tomas in the home above it. They might feel they deserve a share of the business or be glad the responsibility isn't theirs. Details are open to plotting.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p><p><span class="label">Mun contact:</span> Discord: shannn_n · <a href="https://www.tumblr.com/defendingtheice">@defendingtheice</a></p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Parents</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Tomas Acosta de Visser</a></p>
  <p><span class="label">Name / age:</span> UTP · late 50s or older</p>
  <p><span class="label">Suggested FCs:</span> Latina POC mother; Dutch, European, or white father</p>
  <p class="description">Tomas's parents connected over their love of food, cooking, and baking. They married, opened a quaint bakery in Colbyville, and lived in the shophouse above it. They raised or adopted five children who helped in the business as they grew up. Some followed their parents' footsteps while others pursued different paths. Their family history and relationships are open to plotting.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p><p><span class="label">Mun contact:</span> Discord: shannn_n · <a href="https://www.tumblr.com/defendingtheice">@defendingtheice</a></p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="platonic">
  <div class="card-top"><h3 class="card-title">Loyal Customers</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Tomas Acosta de Visser</a></p>
  <p><span class="label">Name / age:</span> UTP · any age</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">The family bakery has served Colbyville for generations. Some customers have been coming since the beginning, with their orders memorized and their favorites personally packed. They've watched Tomas and his siblings grow up and seen the bakery evolve. Tomas holds their opinions in high regard.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="platonic rivalry">
  <div class="card-top"><h3 class="card-title">Schoolmates &amp; Peers</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Tomas Acosta de Visser</a></p>
  <p><span class="label">Name / age:</span> UTP · 20s–30s; classes of 2013–2021</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">Tomas grew up in Colbyville before leaving for Paris. He was a quiet kid who spent much of his time at the bakery or school, so he had few close connections. Your character might have liked him, disliked him, or barely remembered him. Old friendships, rivalries, and awkward reunions are welcome.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="professional platonic">
  <div class="card-top"><h3 class="card-title">Market Regulars</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Tomas Acosta de Visser</a></p>
  <p><span class="label">Name / age:</span> UTP · any age</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">Tomas visits markets and farms to find ingredients and inspiration for the bakery. He's terrible at saying no to interesting offers and often buys more than planned. He's known for softly chatting with vendors and buying from nearly everyone, and he's becoming a familiar face at Carroll's markets too.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="professional">
  <div class="card-top"><h3 class="card-title">Bakery Staff</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Tomas Acosta de Visser</a></p>
  <p><span class="label">Name / age:</span> UTP · any age</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">What started as family labor has grown into a business that needs skilled staff. Tomas hires people with their own specialties in breads, pastries, and more, and enjoys learning their techniques. Former staff may have followed the family to Carroll, while others could be new hires.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="professional platonic rivalry ex-romantic">
  <div class="card-top"><h3 class="card-title">Paris Connections</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Tomas Acosta de Visser</a></p>
  <p><span class="label">Name / age:</span> UTP · any age</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">Tomas spent five years in Paris pursuing his dreams. He might have met your character as a roommate, mentor, fellow kitchen trainee, colleague, friend, rival, or romantic interest. These connections can be carried into the present or explored through memories of his time abroad.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<!-- ASHTON RYDER -->
<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Family Connections</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Ashton Ryder</a></p>
  <p><span class="label">Name / age:</span> UTP · flexible</p>
  <p><span class="label">Suggested FCs:</span> Open to plotting</p>
  <p class="description">Family connections for Ashton are open to development. Cousins and extended family members can have long-standing ties to the Ryders or have returned to Carroll after time away. Contact the character's writer to discuss family history and possible dynamics.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="platonic">
  <div class="card-top"><h3 class="card-title">Old Friends</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Ashton Ryder</a></p>
  <p><span class="label">Name / age:</span> UTP · similar age</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">People who knew Ashton growing up in Carroll, whether they stayed close or drifted apart. They might have shared classes, sports, or formative memories. Old friendships can pick up where they left off or reveal that time has changed them.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="platonic rivalry">
  <div class="card-top"><h3 class="card-title">Friends &amp; Rivals</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Ashton Ryder</a></p>
  <p><span class="label">Name / age:</span> UTP · similar age</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">A connection for someone who can challenge Ashton, tease him, or compete with him. The relationship could be affectionate, competitive, complicated, or a mixture of all three.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<!-- BIRCH ROSE -->
<article class="card" data-new="no" data-status="open" data-types="platonic">
  <div class="card-top"><h3 class="card-title">Friends &amp; Acquaintances</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Birch Rose</a></p>
  <p><span class="label">Name / age:</span> UTP · flexible</p>
  <p><span class="label">Suggested FCs:</span> Any</p>
  <p class="description">Friends, acquaintances, and people Birch has met through life in Carroll. Connections can be cozy and familiar or more complicated, depending on the characters involved. Contact the writer to develop a dynamic.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<!-- ERIC SANDERS -->
<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Family Connections</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Eric and Zach Sanders</a></p>
  <p><span class="label">Name / age:</span> UTP · flexible</p>
  <p><span class="label">Suggested FCs:</span> Open to plotting</p>
  <p class="description">Extended family members connected to the Sanders family. Please read Eric's and/or Zach's biography for family details, and contact the writers to discuss how your character fits into the family tree.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Anne Sanders — Mother</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Eric and Zach Sanders</a></p>
  <p><span class="label">Name / age:</span> Anne Sanders · early 60s</p>
  <p><span class="label">Suggested FCs:</span> Julianne Moore</p>
  <p class="description">Anne began as a teenage model before an agent guided her into acting. She met Noah at 26, and their private relationship became public when they starred together as romantic leads. They became a beloved Hollywood power couple who share a love of Asian cuisine, culture, and travel. At 31, Anne welcomed twin boys. She and Noah have since moved from New York to Los Angeles.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p><p><span class="label">Mun contact:</span> <a href="https://www.tumblr.com/zachreeve">@zachreeve</a> · <a href="https://www.tumblr.com/esanders">@esanders</a> or Discord</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Noah Sanders — Father</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Eric and Zach Sanders</a></p>
  <p><span class="label">Name / age:</span> Noah Sanders · early 60s</p>
  <p><span class="label">Suggested FCs:</span> Pierce Brosnan</p>
  <p class="description">Noah comes from a cinematic family: his father was a respected director and his mother a costume designer. He began acting as a teenager and grew up spending time at his family's secluded lakeside retreat, where he developed a passion for muscle cars. He met Anne at 31; they became a beloved Hollywood couple. Noah was 36 when their twin sons were born. He and Anne have since moved to Los Angeles.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p><p><span class="label">Mun contact:</span> <a href="https://www.tumblr.com/zachreeve">@zachreeve</a> · <a href="https://www.tumblr.com/esanders">@esanders</a> or Discord</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="platonic">
  <div class="card-top"><h3 class="card-title">Old Hollywood Friends</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Ingrid Hawkins</a></p>
  <p><span class="label">Name / age:</span> UTP · 30s</p>
  <p><span class="label">Suggested FCs:</span> UTP</p>
  <p class="description">These characters know Ingrid's family and can tease her about living in Carroll and returning to coaching. The dynamic can be affectionate and playful or more malicious, depending on the character.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="professional">
  <div class="card-top"><h3 class="card-title">Former Cheerleading Coach</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Ingrid Hawkins</a></p>
  <p><span class="label">Name / age:</span> UTP · 50+</p>
  <p><span class="label">Suggested FCs:</span> UTP</p>
  <p class="description">In high school, Ingrid was flighty and easily distracted, and she and her coach didn't always see eye to eye. Now Ingrid has taken over the coaching position, and they'll need to find common ground. A sweet mentor relationship is welcome.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No</p></div>
</article>

<!-- IRVIN BLOOM -->
<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Older Sister</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Irvin Bloom</a></p>
  <p><span class="label">Name / age:</span> UTP · 40+</p>
  <p><span class="label">Suggested FCs:</span> Britt Lower, Rebecca Hall, or UTP</p>
  <p class="description">Irvin and his sister have always had a good relationship. They may annoy each other, but they've always had each other's backs, even when Irvin moved away from Carroll. She can have stayed in town or returned later. Open to plotting.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p></div>
</article>

<article class="card" data-new="no" data-status="open" data-types="ex-romantic">
  <div class="card-top"><h3 class="card-title">The Ex-Fiancé</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Irvin Bloom</a></p>
  <p><span class="label">Name / age:</span> UTP · 35+</p>
  <p><span class="label">Suggested FCs:</span> Dev Patel, Robert Pattinson, Assad Zaman, or UTP</p>
  <p class="description">Irvin was engaged to this character in London and believed they'd spend their lives together. The relationship ended a week before the wedding. Two months later, Irvin discovered his ex had moved on with someone “better.” The reason for the breakup and why the ex is now in Carroll are open to plotting.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Yes</p></div>
</article>

<!-- JESSE COWEN -->
<article class="card" data-new="no" data-status="open" data-types="familial">
  <div class="card-top"><h3 class="card-title">Older Sister</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Jesse Cowen</a></p>
  <p><span class="label">Name / age:</span> UTP · 37–39; née Cowen if married</p>
  <p><span class="label">Suggested FCs:</span> Sophia Di Martino, Elizabeth Olsen, Poppy Drayton, Shailene Woodley, Emma Watson, or UTP</p>
  <p class="description">Jesse and his sister grew up with an abusive alcoholic father and drug-addicted mother. They were inseparable, with his sister protecting him and raising him in an “us against the world” relationship. When Jesse found her college essays in the trash, he pushed her away with cruel words, hoping she'd leave and build a better life. She has tried to reach him ever since, but Jesse believes he's ruined their bond beyond repair. Their father's failing health could bring her back to Carroll, forcing them to confront their past. A connection full of family angst and complicated love.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> Not required, but welcome</p></div>
</article>

<!-- MAVERICK WHITLOCK-HOLMES -->
<article class="card" data-new="no" data-status="open" data-types="ex-romantic">
  <div class="card-top"><h3 class="card-title">The Ex-Boyfriend</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Maverick Whitlock-Holmes</a></p>
  <p><span class="label">Name / age:</span> UTP · 35+</p>
  <p><span class="label">Suggested FCs:</span> Colin Firth, Matthew Goode, Jeff Goldblum, or UTP</p>
  <p class="description">They dated for several months, possibly nearly a year, but Maverick kept him at arm's length and never introduced him to his family. After Maverick's accident, he withdrew, ended things without explanation, and disappeared. Now he's returned from physical rehabilitation, and the attraction may remain alongside unresolved hurt and unanswered questions.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No, unless you'd like to plot</p></div>
</article>

<!-- THEODORE "TEDDY" ROBSHAW -->
<article class="card" data-new="no" data-status="open" data-types="platonic">
  <div class="card-top"><h3 class="card-title">Best Friend</h3><span class="status">Open</span></div>
  <p><span class="label">Connected to:</span> <a href="CHARACTER-PAGE-URL">Theodore “Teddy” Robshaw</a></p>
  <p><span class="label">Name / age:</span> UTP · 34–38</p>
  <p><span class="label">Suggested FCs:</span> UTP; any gender welcome</p>
  <p class="description">Teddy needs someone who can put up with his dramatics and still have his back. They're tight as thieves: his best friend is usually more grounded, but Teddy brings out their wild side. He supports them just as fiercely as they support him.</p>
  <div class="bottom"><p><span class="label">Contact before applying?</span> No, unless you'd like to plot</p></div>
</article>

</section>

<p class="note">
All connections are marked OPEN by default. Replace CHARACTER-PAGE-URL placeholders with the relevant character pages. To mark a connection as taken, change data-status="open" to data-status="taken" and change the visible status label to Taken. To include a card in Newly Added, set data-new="yes".
</p>
</main>

<script>
(function() {
  const root = document.getElementById('wanted');
  if (!root) return;

  let statusFilter = 'all';
  let typeFilter = 'all';
  let newlyAddedOnly = false;

  const buttons = root.querySelectorAll('.filter');
  const cards = root.querySelectorAll('.card');

  function update() {
    cards.forEach(card => {
      const types = (card.dataset.types || '').split(/\s+/);
      const statusMatches = statusFilter === 'all' || card.dataset.status === statusFilter;
      const typeMatches = typeFilter === 'all' || types.includes(typeFilter);
      const newMatches = !newlyAddedOnly || card.dataset.new === 'yes';
      card.hidden = !(statusMatches && typeMatches && newMatches);
    });
  }

  buttons.forEach(button => {
    button.addEventListener('click', () => {
      const group = button.dataset.group;
      const value = button.dataset.value;

      if (group === 'status') {
        statusFilter = value;
        root.querySelectorAll('[data-group="status"]').forEach(item => item.classList.remove('active'));
        button.classList.add('active');
      } else if (group === 'type') {
        typeFilter = value;
        root.querySelectorAll('[data-group="type"]').forEach(item => item.classList.remove('active'));
        button.classList.add('active');
      } else if (group === 'new') {
        newlyAddedOnly = !newlyAddedOnly;
        button.classList.toggle('active', newlyAddedOnly);
      }

      update();
    });
  });

  update();
})();
</script>
</body>
</html>
