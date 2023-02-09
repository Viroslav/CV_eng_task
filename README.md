# CV_eng_task
1 Task:
1.1) Scrap all the images of the people wearing a particular cloth. 
1.2) Scrap all the images of the cloths (not worn on somebody) 
1.3) Scrap all the colors of the particular image of a person and its corresponding cloths. (This is a bonus, totally optional)
All this was done. Photos of cloths and people can be found in https://drive.google.com/drive/folders/1fhitPv8nnbMcbOzURJ-OQHp4sn-nAdTB. Was a little bit hard to deal 
with capthca, I tried to use Selenium, but there is some problem with collab and Selenium and as I work with Collab server becauese they use American servers and site 
works without vpn, I decided to use time outs to not be banned. So it works, I downloaded all clothes in all colors around 1200 pictures. 

2 task:
first of all I used padding to get the same size of pictures. Then I used UNET to make a segmentation using the mask. Cut the mask from IMG and then normalized and 
get the img with applied mask on blue background. 

![https://github.com/Viroslav/CV_eng_task/blob/main/2_task.png](https://raw.githubusercontent.com/Viroslav/CV_eng_task/main/2_task.png)

P.S. more comfortable viewing on Collab https://colab.research.google.com/drive/1ayDus2cbNhRyhYz2Z25EVGJdPV-E3JQj?usp=sharing
