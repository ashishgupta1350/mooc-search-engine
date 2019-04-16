# mooc-search-engine
BM-25 Search Engine for mooc search.


### User requirements:
The search engine allows users to type in key words/ phrases into the system. The system in turn returns the list of top 20 moocs it deems the best match. There are so far 17000 real moocs (2018 - Kaggle moocs dataset) in the database.
To run the system, just run the code(see system requirements) and on the last block, type in the queries. 


### System requirements:
1) The queries should be processed in <1 second.
2) The system is secure and does not more than 2 bad results in top 10 results.
3) The system should produce similar results to the mooc searched as well.
4) The system runs of python.
5) The data is not loaded again and again. Once a mooc is added, it runs without executing the entire code.
6) The code pipeline's bow model should be saved locally and preloaded to avoid restarting the engine and rerunning the app(left)

### Things left:
1) Feedback loop
2) Testing loop and adding a feedback mechanism.
3) Weighted search for user defined preference( Not important)
