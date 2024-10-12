-General Steps-
Predict the next word in the sequence
Feed old input plus a new output word as the next input
Make the output a one-hot encoded label over entire corpus of desired text outputs
Utilize categorical cross entropy loss function as the output will be multi-class

Model Architecture: Bi-LSTM, Embedding

Epochs: 200

Input = "i am just a model"

Total Words Predicted = 100

Output = "i am just a model little bit more just a little bit more just a club secret question watch watch depressed answer refuse answer tambourine note mans message whole harm refuse answer scar block tin sunshine masters figure intention flash chance heal musics block learn answer street answer tomorrow sea door chill mean that everybody before you could have a memory new babe to show blues pick teaser attic spotlight cheeks merry guiding daylight tone weary eyes knew hell am explain grab stone huh write figure bouncer answer figure sidewalks as hell let think rainbow as stay held passing coat answer ahhaha escape drums paris"

i am just a model little bit more just a little bit more...

