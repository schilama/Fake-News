# Fake News Detection Leveraging Linguistic Features

This repo is adapted from https://github.com/strubell/LISA <br/>

Follow the instructions in https://github.com/schilama/Fake-News-Data-Processing to pre-process the data. Store it in the `data` folder.  

Download GloVe embeddings and store them in the embeddings folder.  

To train: <br/>
`bin/train.sh config/fakenews_majority_vote.conf --save_dir=model` <br/>
`bin/train.sh config/fakenews2.conf --save_dir=model2`

To evaluate: <br/>
`bin/evaluate.sh config/fakenews_majority_vote.conf --save_dir=model` <br/>
`bin/evaluate.sh config/fakenews2.conf --save_dir=model2`
