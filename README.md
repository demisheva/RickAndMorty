# RickAndMorty
<p>A simple “Rick and Morty” application https://rickandmortyapi.com/api/character/”character number”</p>
<p>GitHub Pages <a href="https://demisheva.github.io/RickAndMorty/">demisheva.github.io/RickAndMorty/</a></p>

<h1>Task</h1>
<p>Implement a simple “Rick and Morty” application.</p>
<p>NOTE: All styles are up to you (don’t waste much time on design).</p>
<p>When the application is loaded I can see the section with characters images (it should be empty on first load). In the top-center, I can see the text input and search button which allows me to search a character from API. The list should consist last five searched characters. Newest characters from top to bottom. If character not found there should be displayed alert window with “Character not found” text. If searched character is already in the list there should be displayed an alert window with “Character is already in the list” text. Under character list I can see a Load More button if searched characters more than five. When I click Load More button there should be displayed another five characters and auto- scroll to the bottom of the page. Each character could be removed. When I press the "Remove" button then should be displayed confirm window and if I clicked “Ok” the character should be removed from the list, if “Cancel” – the confirm window should be hidden.</p>
<p>API helper: https://rickandmortyapi.com/api/character/”character number”</p>
<p>Features:</p>
<ul>
    <li>Search new character</li>
    <li>Remove character from the list</li>
    <li>Show delete confirm window</li>
    <li>Show not found alert</li>
    <li>Show already exist alert</li>
</ul>
<p>Pay attention:</p>
<ul>
    <li>you can edit app.js and styles.css files but NOT index.html</li>
    <li>all DOM manipulations must be done in app.js file</li>
    <li>After refreshing the page all previously searched characters should be shown. (Please use</li>
    localStorage for storing data)
</ul>
<p><b>RESTRICTIONS</b></p>
<ul>
    <li>Editing index.html is forbidden</li>
    <li>You don’t need to spend much time on implementing design of the application</li>
</ul>