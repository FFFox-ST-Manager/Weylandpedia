# Character Information

<div class="character-grid">

<!-- Character Card Template -->
<div class="character-card">
  <div class="character-image">

  </div>
  <div class="character-details">
    <h3>Kressa</h3>
    <p class="character-trait"><strong>Species:</strong> Okamimimi (Wolfgirl)</p>
    <p class="character-trait"><strong>Age:</strong> 24</p>
    <p class="character-trait"><strong>Room:</strong> #318</p>
    <p class="character-description">A brilliant, shy tech enthusiast with violet hair and pink highlights. Has a tendency to ramble when excited about technical topics.</p>
  </div>
</div>

<!-- Another Character Card -->
<div class="character-card">
  <div class="character-image">

  </div>
  <div class="character-details">
    <h3>Drake</h3>
    <p class="character-trait"><strong>Species:</strong> Okamimimi (Wolfboy)</p>
    <p class="character-trait"><strong>Age:</strong> 21</p>
    <p class="character-trait"><strong>Room:</strong> #271 (with Blake)</p>
    <p class="character-description">A quiet, intelligent wolfboy who excels in his Arcane studies. Has a bushy wolf tail and doesn't drink coffee.</p>
  </div>
</div>

<!-- Add more character cards as needed -->

</div>

<style>
.character-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
  margin: 20px 0;
}

.character-card {
  display: flex;
  border: 1px solid var(--SmartThemeBorderColor);
  border-radius: 10px;
  overflow: hidden;
  background-color: var(--SmartThemeBotMesBlurTintColor);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.character-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.character-image {
  width: 120px;
  flex-shrink: 0;
}

.character-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.character-details {
  padding: 15px;
  flex-grow: 1;
}

.character-details h3 {
  margin-top: 0;
  margin-bottom: 10px;
  color: var(--SmartThemeBodyTextColor);
}

.character-trait {
  margin: 5px 0;
  font-size: 0.9em;
}

.character-description {
  margin-top: 10px;
  font-style: italic;
  font-size: 0.9em;
}
</style>
