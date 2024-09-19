## TeluguWordRecognizer

> Note : This below instructions are intended to work on this project via Google Colab only. If you are willing to work on your personel pc please raise an issue so that I can help you

The Telugu OCR for recognizing Handwritten words.

### step-0 create a folder in drive and name it WordTOCR (if you wish to choose your own name, you need to change the directory name in final_Word_TOCR.ipynb file) and copy all the files in this repository.

### Step-1 Downloading Dataset
create a new folder outside of WordTOCR and name it "handwritten_telugu_word_dataset"
Download the dataset from the link: https://drive.google.com/drive/folders/1OWdHJhDH-x6n257ck4avON7eIybb5aIR?usp=share_link and store it in  "handwritten_telugu_word_dataset". 

### step-2 Downloading the weights
Download the weights form the link: https://drive.google.com/drive/folders/1r_UYkVKrSZDG6Uf93e03-AmYWwVHrIem?usp=share_link rename in to Training and store it in the WordTOCR folder with final_Word_TOCR.ipynb

### Step-3 Running the file final_Word_TOCR.iynb
--> The output is stored in final_text.txt file which is automattically created by program in the WordTOCR folder.


### important note: GPU processers are necessory for smooth execution. To access the GPU in colab convert the runtime to GPU.
