# Google Colab Tutorial

Colab is a Google’s free cloud service which will let you run your deep learning or machine learning models in cloud.

### Project file
Download .ipnyb file from github repository https://github.com/developerNishtha/Twitter-Sentiment-analysis

### Uplaod On Drive
Upload .ipnyb file on your google  drive


### Creating New Colab Notebook

* Open your colab
* Select .ipnyb file from drive section and open

### Download kaggle.json API
Open your kaggle account go to your profile and download API json, save with name kaggle.json

### Upload kaggle.json
In colab got files > uploade to session storage and select kaggle.json api from your computer.   



### API Set-Up
```
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 /root/.kaggle/kaggle.json
```

### Download Dataset

```
!kaggle datasets download -d kazanova/sentiment140
```

### Extract Dataset Zip File
```
import zipfile
zip_ref = zipfile.ZipFile('/content/sentiment140.zip', 'r')
zip_ref.extractall('/content')
zip_ref.close()
```

<b> This project was done a part of our Semester-5 course on Data Analytics and Visualization. </b>

<h3 align="center"><b>Mentor by:</b></h3>

<div align="center">	
<table style="border:1px solid black;margin-left:auto;margin-right:auto;">  
  <tr>
<td>
  <img src="https://media.licdn.com/dms/image/D4D03AQEXUW2fphJQgg/profile-displayphoto-shrink_800_800/0/1669448441593?e=1680739200&v=beta&t=E8NVc-0Rb9Ul8m0tzVYz-2c1T5_QuoEZtTOL4z84rys" width="150" height="150"/>
     
    Dhaval Deshkar

<p align="center">
<a href = "https://www.linkedin.com/in/dhaval-deshkar-6b35ba195/"><img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/></a>
</p>
</td>
</tr>
</table>
</div>

<h3 align="center"><b>Developed by: </b></h3>
<div align="center">
<table style="border:1px solid black;margin-left:auto;margin-right:auto;">  
  <tr>
<td>
  <img src="https://media.licdn.com/dms/image/D4D03AQFKXTj6Sc-4Iw/profile-displayphoto-shrink_400_400/0/1667303085238?e=1680739200&v=beta&t=cNLzSVqe42wGs7xZg084xsPFqHUhmsEQvMSrlc6v4Rs" width="150" height="150"/>
     
    Shah Nishtha

<p align="center">
<a href = "https://www.linkedin.com/in/nishtha-shah-b0909b212/"><img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/></a>
</p>
</td>

<td>
  <img align='center' src="https://avatars.githubusercontent.com/u/79783828?s=400&u=e7e94e4c752005f4263a121d86fb25c75a247f54&v=4" width="150" height="150">
     
    Het Patel

<p align="center">
<a href = "https://www.linkedin.com/in/hetpatel2312/"><img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/></a>
</p>



</tr>
</table>
</div>
