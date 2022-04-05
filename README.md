# Smart-Evaluation

Nowadays, due to the pandemic, people generally avoid going to a crowded place.
This pandemic has also impacted our education system as people currently have
fear. So due to this, there was a tremendous increase in the use of an online ex-
amination system, a system used to evaluate the individual’s knowledge. But there
is a significant drawback of this system, as many individuals use online sources to
answer the question asked to them. Because of this drawback, deserving candidates
were suffering as despite using their mind, they are getting similar marks that can-
didates who are just copy-pasting. This also has an increasing burden on the course
instructor as they have to face difficulty in determining whether the response given
by candidate was by using own mind or by using online available sources. So reduce
the burden on the course instructor a system need to be developed which will help
them to check the plagiarism in the candidate response.
Notebook Plagiarism Checker tool aims to simplify the process of checking the note-
book by an individual for plagiarism. This tool will be leveraging the capabilities of
text detection and text recognition mechanism. This checker tool will recognise the
character from the notebook’s image and convert the recognised text into an editable
text file. This tool is based on artificial neural networks. Prepossessing methods will
enhance the images which will help neural network to capture more features from
the input image. CNN layers was used to extract the feature from the prepossessed
image which were the passed to RNN layers which will help to get the characters
from the input image. The generated distribution over character were then decoded
using connectionist temporal classification function which will generated the desired
result. For model building and training, IAM handwritten dataset was used.
