
# Ali_Khatami_MERN2(Learning from the video of Mohammed Taheri)

### Prerequistic

For this at firstvwe need to have knowledge about javascript function and React <br>

we need to have node js install in our computer <br>

we can use VS code and chrome <br>

![m1](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/8581ea7e-1134-4b41-bc5c-7558ede32e2d)

we have created the above folder for our project <br>

![m2](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/b65676e6-577c-4264-a855-a010933fc1b8)

code:

```
npm init -y

```
we typed the above command for the package.json folder at backend <br>

![m3](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/f28d318b-deec-4de9-a283-3fefedc42d2c)
we have use the line of code which is export keyword and import keyword <br>


now let us add two packages to our project express.js  and nodemon <br>

![m4](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/ff571b90-b135-4848-9e2e-61cfab08610f)

code:

```
npm i express nodemon

```


then we typed the above command 



we will use  Express as our framework and will use nodemon for restarting our server automatically <br>


we will use nodemon for restarting our server automatically unchanged <br>


now add script to script section <br>


![m5](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/18dcbf16-db0a-4918-b5d6-c0345308a417)


here start will run the project nodejs environment <br>


dev will run the project with nodemon <br>

we use these commands in development <br>


![m6](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/f7d12001-bc1b-4b0d-b495-7dc3618d26cc)

here we have created a file name index.js it will be the stater of our project <br>



![m7](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/3d1389e3-86c2-41d9-9bb8-df897764581c)


at first line we add express.js framework <br>

then by the second line we defined a new variable for it <br>


then we will mke it listen to a port <br>

it is better solution to seprate our code fom different files and folders <br>


![m8](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/ff73ff90-511e-4dbe-86f5-1455c3a96e65)

For the port we have created the above file <br>

![m9](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/6f721ac4-8312-4139-9930-2625eaf241e9)
 Thus we have defined our PORT in the above file <br>

 
![m10](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/dffafd89-dbc0-4a9c-9eed-578db21a23ee)

we have import PORT by using the above line of code <br>


![m11](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/c285db3e-93a2-4aa3-bdfc-48dc75d353d0)

we have use the above function for listening to our PORT, after PORT we pass a callback function  <br>
then we have used console.log to show everything is okay <br>

![m12](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/1bb66dd8-dc48-463a-aae2-62456c9a7572)

Code:

```
npm run dev

```

if we run the above code we get the above message at last part <br>
we can understand that our server is running <br>


![m13](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/cdd132f8-0af1-4132-addd-2b99ce307757)

we can get the above error message if we go to the localhost port  <br>

![m14](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/3bd080d5-8450-4564-bd37-99d04279b23b)

now we will go to the above arrow marked part <br>


![m15](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/522d82b2-881e-4632-bcd1-99833e733e6f)


now we will click the above network section <br>

![m16](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/aed1a6ca-153e-4d0b-88fe-a7413228e04e)

In the above we can see request to localhost nad it has status of 404 <br>


![m17](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/a1754027-4f86-4350-ac0b-52ef2764a39e)

In the abocve we can see three sections <br>


![m18](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/dee6c4ca-b6ab-4e40-9b92-aefa90b08be3)

In the above we can see Request URL, Request method and status code <br>


the defailt HTTP route of this server is slash <br>


In index.js we will use express framework to create our HTTP route <br>

![m19](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/b833b7ed-7ddc-4f9d-9c8e-82b3e7e2b568)

here we use the above method to get resources from the server <br>


![m20](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/8fc356fe-4f6e-4ff4-9feb-9bf933aa0437)


here as afirst parameter we use slash , <br>
second prarameter is the callback function that handles this request <br>

in this callback function we will receive request and response <br>

and we can mange both of them <br>

we can log the request and also return any message with our response <br>

we can send HTTTP status code with any message we want <br>

![m21](https://github.com/C191068/Ali_Khatami_MERN2/assets/89090776/5c74e0ac-6c7c-4172-b6a7-e1b9d9a99385)

the above vresult e get in our server <br>














