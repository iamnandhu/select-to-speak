
# Select - to - Speak🔊

![Image](https://play.ht/blog/wp-content/uploads/2020/12/1_7HOERatJ83E1KkKr1SVAug-1140x503.png)

An NLP based chrome extension that processes the selected text on the screen and converts it into natural sounding speech built with **AWS Amplify**. This extension also makes use of **AWS Amplify Predictions** to add machine learning to the app.


## Run Locally

Install and configure Amplify CLI in your local machine - [Amplify](https://docs.amplify.aws/)

Clone the project

```bash
  git clone https://github.com/iamnandhu/select-to-speak.git
```

Go to the project directory

```bash
  cd select-to-speak
```

Install dependencies

```bash
  npm install
```
Initialize new Amplify project

```bash
  amplify init
```
Create the services

```bash
  amplify push --y
```
Build the extension

```bash
  npm run build
```
To test the extension locally
```
--Go to [Extensions](chrome://extensions)
--Enable Developer mode
--Click on Load unpacked and select the build folder
```
## Supported Languages

**Inputs**

`Dutch`  `Portughese`  `English`  `Italian`  `French`  `Spanish`

**Outputs**

`Arabic`  `English `  `Chinese`  `Dutch`  `Spanish`  `Portugese`  `Danish`  `Hindi`  `Italian`  `Japanese`  `Korean`  `Norwegian`  `Polish`  `Russian`  `Swedish`  `Turkish`
