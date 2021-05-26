# NLP
## The repo consists of 3 different files each addressing different questions
### 1. Genre Classification:
It consists of a pre-training pipeline to process the Lyrics in the dataset 
A comparison between different models like RNN, CNN, LSTM are done. 
Pre-trained embeddings and embeddings built from the dataset are compared for their performances.

### 2. Transfer Learning:
The models built is the Genre Classification are used to predict the singer of the song using transfer learning.

### 3. Language Modelling:
A language generation model is built using GRU network. A seq2seq model is built for the generation of the lyrics
This model can generate lyrics of different genres it is trained on

Sample output:

tf.Tensor([b'dancen sleep turn away from hi lyfitim ankow joy the show down now i tell thi night is fruzin begrie glow on i didnt need a toot in me not hold our hope it hurt feel enough and if is let get realli just a littl bite on cold street at deceas and pain they step malestim unfold it life is done miceri chanc but they catch me with it get betray weak the fresh is in faith is thi cattl secreci two behold dri it to desarv repent men but baggag te a tool be after wrong their ingani man crawl overdustain rminesion live lit trembebl onc age we will end over anoth night destind manifest monstrvist drive by their knee and the moon these bite of the earth they seek assam no one spot hi keeph so far stop their land of beast romain pumpin poison rule cant will be frustrat a culsul depend come inscroudlin fall scorn and cunt as i came tri to pay you but still i am i what left to spread in mind what you do what i remeng i pay fade i rememb i am uni beyond that it hope i shall prey i seek im in the belief i s'], shape=(1,), dtype=string) 


