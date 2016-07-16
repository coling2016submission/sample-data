Proposition Banks - Example Data
--------------------------------

A data file compressed in 7zip format containing sample data accompanies this submission.

CONTENTS of the data file:
--------------------------

The data file contains sample data from each of the 3 Proposition Banks generated with our approach. 
For each PropBank, we present 100 randomly drawn sentences with SRL information and 100 verb
frame files. The easiest way to inspect the data is using a Web browser on the frame files.  


FORMATS of the files:
---------------------

- Each sample of 100 SRL annotated sentences is a plain text file in CoNLL-X format. Next to default syntactic
and shallow semantic labels, we include the English source sentence in the "extra" field of the root word of
each sentence. 

- The verbal frames are in the folder frames/ in each language subfolder. Each verbal frame is an HTML file formatted
the same way as the English Proposition Bank frame files (http://verbs.colorado.edu/propbank/framesets-english/). 
The best way to view the frame files is using a Web browser. 


LIST of files in the data file:
-------------------------------

  ChinesePropositionBank/chinese-propbank-sample.txt		Sample of 100 sentences with SRL information
  ChinesePropositionBank/frames/				Folder with frame files for 30 verbs

  FrenchPropositionBank/french-propbank-sample.txt		Sample of 100 sentences with SRL information
  FrenchPropositionBank/frames/        				Folder with frame files for 30 verbs

  GermanPropositionBank/german-propbank-sample.txt		Sample of 100 sentences with SRL information
  GermanPropositionBank/frames/					Folder with frame files for 30 verbs
 

INTERESTING verbs:
------------------

Some verbs can evoke more than one frame. These verbs can be found by sorting the files in the frames/ folder
by filesize. Verbs that evoke multiple frames have description and examples for each sense, and their frame 
files are therefore largest. 

Interesting verbs in German include: annehmen (3 frames), abziehen (2 frames) and angeben (2 frames). 

Interesting verbs in French include: aller (3 frames), accorder (2 frames) and agir (2 frames).

Interesting verbs in Chinese include: 打 (3 frames), 闻 (2 frames) and 留 (2 frames). 


COPYRIGHTS of the files:
------------------------

Please do NOT redistribute these files. The full datasets will be released officially through our website.
