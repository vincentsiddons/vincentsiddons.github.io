<style>
  .page-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    font-family: sans-serif;
    padding: 2em;
    max-width: 1000px;
    margin: 0 auto;
  }

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
  }

  .project-item img {
    width: 100%;
    border-radius: 8px;
    border: 1px solid #ddd;
  }

  .project-title {
    font-weight: bold;
    font-size: 1.2em;
    margin-bottom: 0.5em;
  }

  .project-caption {
    margin-top: 0.75em;
    font-size: 0.95em;
    color: #444;
  }

  .section-header {
    font-size: 2em;
    font-weight: bold;
    margin-top: 3em;
    text-align: center;
  }

  @media (max-width: 600px) {
    .project-item {
      width: 100%;
    }
  }
</style>

<div class="page-container">

  <!-- About Me section -->
  <section class="project-item">
    <div class="project-title">About Me</div>
    <img src="me.jpg" alt="Photo of me">
    <div class="project-caption">
      I am researching how language and vision models interpret and generate metaphorical images by fine-tuning multimodal models and analyzing their outputs. My work involves dataset creation, model training, and evaluation to improve metaphor understanding in AI.
    </div>
  </section>

  <!-- Projects header -->
  <div class="section-header">Projects</div>

  <!-- Projects grid -->
  <div class="project-item">
      <div class="project-title">Classifying Visual Metaphors</div>
      <img src="no_one_grows.jpg" alt="Visual metaphor project">
      <div class="project-caption">
        I built a classifier to detect visual metaphors in images using a custom dataset of 844   metaphorical and literal ads, leveraging CLIP and perplexity-based embeddings derived from image captions. Using scikit-learn, we trained logistic regression and SVM models. The best F1 score (0.682) came from logistic regression on CLIP embeddings; SVM with perplexity features improved by 1.5 points, highlighting their value for metaphor detection.
      </div>
    </div>
    
  <section class="project-grid">
    <div class="project-item">
      <div class="project-title">Reddit Cat Breed Predictor</div>
      <img src="cats.png" alt="Cat bot project">
      <div class="project-caption">
        I developed and deployed a Reddit bot that predicts cat breeds from user-submitted images using a fine-tuned OpenAI CLIP model. I automated image retrieval and commenting with Python, resulting in increased user engagement and high prediction accuracy.
      </div>
    </div>
  </section>
</div>

