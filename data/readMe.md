Toxicity detection: Toxicity detection refers to identifying and classifying content or interactions considered harmful, offensive, or inappropriate within digital platforms, such as social media, forums, or online communities. This involves analyzing textual, visual, or audio data to detect elements such as hate speech, harassment, threats, profanity, or other forms of harmful behavior.

Dataset: The dataset provided comments on Wikipedia and annotated by a toxic comment (1) or not (0). Three files are provided: train, valid, and test. The train and validation set has the following columns 
- comment_id
- comment 
- split 
- toxicity (1 : toxic and 0 : non-toxic)

The test has the following columns 
- comment_id
- comment 
- split 
- out_label_model_Gen (for now, it is -1, you need to fill it by 0/1 by Generative Model's output) 
- out_label_model_Dis (for now, it is -1, you need to fill it by 0/1 by Discriminative Model's output)

Data Selection

You will select a dataset based on the last digit of your Student Registration id. 
All digits one, not rs12345 or SHER12345

You will select based on the last digit of your Student Registration id

Your Reg id     - Data

12345670        – 0
12345671        – 1
12345672        – 2
12345673        – 3
12345674        – 4
12345675        – 5
12345676        – 6
12345677        – 7
12345678        – 8
12345679        – 9

 
