# Tv_script_generation

Tv_Script_generation project is a part of DEEP LEARNING nano degree of UDACITY. In this project, I generated own Seinfeld TV scripts using RNNs. I'll be using part of the Seinfeld dataset of scripts from 9 seasons. The Neural Network I built will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

# Project Execution and Dependencies

 1) Clone the repository and navigate to the downloaded folder.
 
     ``` python
     git clone https://github.com/shankar939014/tv_script_generation.git
     
     ```
 
 2) If you have GPU, train the RNN network using the same else it is recommended to use Cloud service suchs as AWS, GCP. They are providing
     Virtual Machines with pre installed libraries and frameworks. I have taken aws p3.2x instance which is having pytorch 0.4 with cuda 9.
     
 3) Dataset is provided in the repo. Though the data is less ( 3.4 MB) we can generate the fake script after substantial training. You are          encouraged to train the model with more data. Only problem is it will take more time to train.
 
 4) Open the jupyter notebook dog_app.ipynb
  
      ```
      jupyter notebook dlnd_tv_script_generation.ipynb
      
      ```
 5) Model will generate fake script. You can see that there are multiple characters that say (somewhat) complete sentences, but it doesn't have to be perfect! It takes quite a while to get good results, and often, you'll have to use a smaller vocabulary (and discard uncommon words), or get more data. The Seinfeld dataset is about 3.4 MB, which is big enough for our purposes; for script generation you'll want more than 1 MB of text, generally.
 
 6) Below is the script got generated after training the model with suitable hyper parameters which gave loss of 0.4 after running for 100 epochs.
 
 
 jerry: as packets looks) and by the manager or mutual around up with a world sensitive made the manager) get down with the ball mill the inn interests and i was facing.

jerry: yeah, he's thinking her when, he's down the phone!

kramer: hey, look at these this is bogus?

kramer:(shrugging i know her this?

jerry: yeah, in too so, uh, went here.

chauffeur: i'm sorry.

stu: so i guess these finds(gets finger the phone book out of here. and well...

kramer:(to joel) who drive you are in the mirror.

elaine: what? really? really? really? really, thanks. what do i want you running out?

jerry: yeah.

george: sorry, i'm starving here is a paper. eh, all on my lap of people. he's a bit of fact room to have the doctor line, my tellin, hand. he's a bit 2.
    

