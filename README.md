# wikihowImageTextMatch
## Generate dataset (you can skip this part if you need to use the already extracted dataset below)
Run wikihow_crawler.ipynb

## Run the models
1. Get the data from https://drive.google.com/drive/folders/193eMMm84b4fx8i3g0bFavX11ZMPTUTl1?usp=sharing
2. Update the paths in /Siamese Network/Word2vecgensim.ipynb then run the the cells. At the end, you should have two files: article.csv and word2vec_gensim.csv
3. To run the Siamese netwrok, update the paths in /Siamese/siamese_network.ipynb then run it
4. To run the Dual Encoder, update the paths in /Dual_Encoder/Dual_Encoder.ipynb then run it

## Start the tests
Open wikihow_model_tester.ipynb, update the models paths to point to the models generated in the Run the models section above
