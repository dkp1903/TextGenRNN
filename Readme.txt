Project : Legal Text Generation Using Recurrent Neural Networks

Name : Dushyant Pathak

ID : 201701062

All dependencies are directly installed in the Python Notebooks.
Strongly recommended to use Google Colab with GPU Accelerator.

1. The code contains a number of notebooks, each of which can be run independently of one another.
2. The dataset is a list of XML documents, that can be found at https://github.com/mappingtreaties/ToTA
3. Here are the instructions, assuming that you are using the already created train and test text files and that you are running using Google Colab: 
	A. VanillaRNN code : A Vanilla RNN implementation : dataset_1.txt file needs to be uploaded on Drive.
	B. CharRNN Approach 1 (TensorFlow code) : Run the file, dataset_1.txt and test.txt to be uploaded on Drive.
	C. CharRNN Approach 2 (TensorFlow code) : Run the file, data_1.txt should be uploaded on Drive.
	D. PyTorch Approach : dataset_2.txt should be uploaded on Drive.
	E. BERT Eval : output-1.txt and ref.txt should be uploaded on Drive, according to the Folder path provided in the code.

4. output.txt file will be downloaded during the run of B. The output-1.txt file in E, is some complete sentences extraced from output.txt, since the BERTScore function requires the two comparison files to have the exact same number of sentences.