# Fake-News-LSTM
fake news classifier using bi-directional LSTM
Bidirectional LSTMs are an extension of traditional LSTMs that can improve model performance on sequence classification problems.
What is Fake News??
Many people have been using the term fake news for the last few years, but do they actually know what it looks like? The term has been used so amorphously that it begs a more direct examination. Sensationalist fake news is often used to generate clicks onto a webpage to improve ad revenue. It has also been used to influence public thought.

In problems where all timesteps of the input sequence are available, Bidirectional LSTMs train two instead of one LSTMs on the input sequence. The first on the input sequence as-is and the second on a reversed copy of the input sequence. This can provide additional context to the network and result in faster and even fuller learning on the problem.
