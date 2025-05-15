<style>
.project-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 40px;
  margin-top: 2em;
}

.project-item {
  width: 300px;
  text-align: center;
  font-family: sans-serif;
}

.project-item img {
  width: 100%;
  border-radius: 8px;
  border: 1px solid #ddd;
}

.project-caption {
  margin-top: 0.75em;
  font-size: 0.95em;
  color: #444;
}
</style>

<div class="project-grid">
  <div class="project-item">
    <img src="{{ site.baseurl }}cats.png" alt="Cat bot project">
    <div class="project-caption">
      Developed and deployed a Reddit bot that predicts cat breeds from user-submitted images using a fine-tuned OpenAI CLIP model. Automated image retrieval and commenting with Python, resulting in increased user engagement and high prediction accuracy.
    </div>
  </div>
  
  <div class="project-item">
    <img src="{{ site.baseurl }}me.jpg" alt="Photo of me">
    <div class="project-caption">
      I am researching how language and vision models interpret and generate metaphorical images by fine-tuning multimodal models and analyzing their outputs. My work involves dataset creation, model training, and evaluation to improve metaphor understanding in AI.
    </div>
  </div>
</div>
