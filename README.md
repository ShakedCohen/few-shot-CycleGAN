# few-shot-CycleGAN
Training CycleGAN for style-transfer, given a very limited data as input - 30 target domain instances. Many methods from the latest publications on the topic were utilized, acheiving impressive fidelity score.

See report for more details.

Code:

Training Notebook
https://colab.research.google.com/drive/1V49FU2Pauee9NvjS4qhnNXFw4wUVEti_?usp=sharing
Inference Notebook
https://colab.research.google.com/drive/1H-CETjZltYqxgrzAA6SaUaV5bvKXj907?usp=sharing
----------
The following Colab notebooks were forked from Robert A. Gonsalves as described in the paper, applying his
idea in our problem domain, with revisions to his code and adaptation to our needs. This code is CC BY-SA
licensed.
Colab notebook scraping Impressionist landscapes paintings of artists born between 1800 and 1950.
https://colab.research.google.com/drive/1oDFC4sfSlQfhq-M9-dQNudZe5hKABySn?usp=sharing
Colab notebook for image preprocessing and resizing to 256x256
https://colab.research.google.com/drive/1cXBPjP1Zw2GHoPlosBLGOW2Jl_ozBImg?usp=sharing
Colab notebook for image filtering with CLIP. Notebook was used to find the top 400 monet-like images,
among the 2080 collected, matching the semantic search phrase "monet painting".
https://colab.research.google.com/drive/1LDgBT3WJg5sZ9knRTBGMbOVuUjXJ18aL?usp=sharing
