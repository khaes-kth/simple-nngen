# Simple-NNGen + Data

This repository contains the code and data for paper [On the Relevance of Cross-project Learning with Nearest Neighbours for Commit Message Generation](http://arxiv.org/pdf/2010.01924) ([doi:10.1145/3387940.3391488](https://doi.org/10.1145/3387940.3391488))

nngen.py file at the root folder contains implementation of Simple-NNGen & EXC-NNGen.

The content of the files in "files/data" is described in the following table.

| File Name                             | Description                                                                            |
|---------------------------------------|----------------------------------------------------------------------------------------|
| bleu_scores                           | scores of each method for tests from each dataset                                      |
| [x].test.msg                          | messages generated by method [x] for tests from cleaned dataset                        |
| filtered-[x].msg                      | messages generated by the algorithm or copied from source for filtered data            |
| msg-word-count                        | data for Figure 1 of paper. First line for training and second line for testing subset |
| nngen-avg-bleu-scores                 | bleu scores for messages generated by nngen for each origin                            |
| number-of-messages-from-the-same-repo | number of messages each algorithm selects from the same repo                           |
| [other/same/unknown]_repo.msg         | nngen.test.msg & test.msg data divided due to the origin                               |
| [test/train].[diff/msg]               | copied from the cleaned dataset                                                        |
| scores_per_origins                    | scores for messages selected by NNGen from each origin                                 |
| [x].projectIds                        | repo_id for each message in [x]                                                        |
| repo-id-to-github.txt                 | maps repo_id to github repository                                                      |
