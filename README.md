![header](https://capsule-render.vercel.app/api?type=shark&color=auto&height=250&section=header&text=Bike%20demand%20prediction%20using%20Random%20Forest&fontSize=30&animation=scaleIn)

### The prediction is supervised learning since we have label (COUNT)
<p align="center">
    <img src="https://user-images.githubusercontent.com/111060150/202733270-e7cd2c72-4a0d-4dcc-8efd-bcc3771b7056.png">
  
</p>
<br/>
<br/>

### The prediction will be analyzed with RMSLE which is more dependent on underfitting
## RMSLE
<p align="center">
    <img src="https://user-images.githubusercontent.com/111060150/202733857-c04c1548-d89a-4b86-b1ae-e58297e45943.png">
  
</p>
<br/>
<br/>

### Exploratory Data Analysis
<p align="center">
    <img src="https://user-images.githubusercontent.com/111060150/202734173-730112f7-e850-4ac7-aeda-31b3dc2df4c2.png">
  
</p>
<br/>
<br/>

### I decided to deal with 0s in windspeed because it seems like unobserved windspeeds are also included in 0.
<p align="center">
    <img src="https://user-images.githubusercontent.com/111060150/202735181-ba96ede3-6055-48d6-bd08-e68cf3e9b531.png">
  
</p>
<br/>
<br/>

### Using RandomForestClassifier, I redistributed windspeed
<p align="center">
    <img src="https://user-images.githubusercontent.com/111060150/202735583-4ab84075-d75a-4d58-8ed5-7713f3273d8f.png">
  
</p>
<br/>
<br/>

### Acheived Kaggle score of 0.41951
<p align="center">
    <img src="https://user-images.githubusercontent.com/111060150/202735805-7f2e0fc4-b5af-4b00-baa1-4b78138b5687.png">
  
</p>
<br/>
<br/>
