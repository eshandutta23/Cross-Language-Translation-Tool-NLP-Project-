# Cross-Language-Translation-Tool-(NLP Based Project)

As part of my project, I developed a Multilingual Translation tool i.e (Cross Language Translation Tool) using pretrained transformer models such as MarianMT and mBART from Hugging Face. 

Created a custom dataset with English sentences and their translations in multiple languages, and fine-tuned the models using the Seq2SeqTrainer API.

The translation performance was evaluated using the BLEU score, where the model achieved a score of approximately 34.98. Also compared the performance of two models i.e (qualitative Evaluation).

Used Python for implementation, Hugging Face Transformers for model loading and training, Pandas for dataset handling, and ipywidgets i.e GradioUI in Google Colab to build a simple user interface that takes user input and displays the translated output in real time.
### DevOps & Deployment (In Progress)
Learning to containerize this project using Docker for easy deployment.
Plan to host it on AWS EC2 and automate updates via GitHub Actions.
