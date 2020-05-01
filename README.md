# Trigger-custom-event-Dialogflow
Create your custom events and trigger those in your code where you need. Such as to trigger a welcome event in client side app by just providing an event name not text response.

## Setup Event on Dialogflow
Create an event in your agent on dialogflow inside any intent

![](/images/image1.png)

## Steps to configure
- Get your project id from your dialogflow agent's console and paste it in project id variable

![](/images/image2.png)

- Click on the service account link and enable dialogflow api

![](/images/image3.png)

- Find the service account for your project id and click on that link.

![](/images/image4.png)

- Click on the edit button

![](/images/image5.png)

- Click on Create a key button

![](/images/image5.png)

- Select Json and download the key in your project folder or anywhere where you want.

![](/images/image6.png)

- Provide the path to your json key file

![](/images/image7.png)

## Usage
```
npm i
node index.js
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)

