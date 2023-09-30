# anonymous
In this dataset, we set out to detfer from the conventional norm in which intent classification datasets are constructed.

For each sentence in the dataset, only a label which identifies the intent label to which the sentence belongs is included.
No slot labels are added to the token inside each sentence.

The goal is to investigate if LLM such as Llama-2, GPT-4 can distinguish correctly sentences which belong to different intent categories, with incontext learning, i.e., prompting. We do not intend to do have fine-tuning on this dataset.
Our target domain is human robot interaction (HRI).

We considered the following intent categories: pet, food, job, hobby, sport, drink. There is one file corresponding to each of these categories in this repository. The files are HRI_intent_1_pet.csv, HRI_intent_2_food.csv, HRI_intent_3_job.csv, HRI_intent_4_hobby.csv, HRI_intent_5_sport.csv, HRI_intent_6_drink.csv

The file named TOTAL_data.csv contains all of the data found in the 6 files HRI_intent*.csv
