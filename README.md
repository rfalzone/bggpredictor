This project scrapes info from Boardgamegeek.com's API, parses XML formatted data, and makes predicitons about new game's popularity.

The Modeling notebook is a subsection of the main Data Compliation notebook.  It contains just the modeling of the gathered data.  The Data compliation notebook contains the process for the gathering of the data, the cleaning of the data, then the modeling

Boardgame.pkl is the raw scraped data.  Boardgameonehot.pkl and dffinal.pkl are both referenced but are too large to attach here, both can be derived by running the cells in the notebook on boardgame.pkl.

X3, Y3, Y2, X2 are all that are needed to run the models.  They are X,Y split data with the target data split into 3 groups and 2 groups, respectively. 
