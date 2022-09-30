# USER PREFERENCE FAKE NEWS DETECTION

DISCLAIMER: This project is not used for any commercialisation, rather only for Academic Purpose. 

Original Code: https://github.com/safe-graph/GNN-FakeNews

Improvement: Added Multihead Attention with 4 heads using GAT 
 																
 																
Made by: 
   Harsh Bijwe,
   Abhishek Pratap Singh,
   Kishore M,
   Murtaza Saifee.
   
> Install requirement.txt files attached, and pytorch Geometric, scatter, sparse using following:

       > pip install -q torch-scatter -f https://pytorch-geometric.com/whl/<torch-version>+<cuda-version>.html
       > pip install -q torch-sparse -f https://pytorch-geometric.com/whl/<torch-version>+<cuda-version>.html
       > pip install -q git+https://github.com/rusty1s/pytorch_geometric.git
       
> If you face any difficulty, follow official link for installation here: https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html

 																
 															
> To run the project file, write following command:-
 													
> python3 Team_Entropy.py dataset_name model_name
 														
NOTE: dataset_name could be either gossipcop/politifact & model_name could be either bert/content
 															  
 															  
It is mandatory to provide dataset name and model name otherwise the program will exit.
 															  
> After writing above commands, the screen will automatically show the Output Accuracy w.r.t. GNN Model and GAT + Multihead Attention Model.
