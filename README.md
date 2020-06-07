<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8" />
  <title>Support Chatbot</title>
  <!-- Load TensorFlow.js-->
  <script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.0.0/dist/tf.min.js"></script>
  <!-- Load the coco-ssd model. -->
  <script src="https://cdn.jsdelivr.net/npm/@tensorflow-models/coco-ssd"></script>
  <!-- Load React. -->
  <script src="https://unpkg.com/react@16/umd/react.development.js" crossorigin></script>
  <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js" crossorigin></script>

  <script src="https://unpkg.com/babel-standalone@6.26.0/babel.min.js"></script>
</head>

<body>

  <h1>ChatBot Demo</h1>
  <!-- Load our React component. -->
  <script src="detect.js" type="text/babel"></script>

  <!-- We will put our React component inside this div. -->
  <div id="root"></div>

<iframe
    allow="microphone;"
    width="350"
    height="430"
    src="https://console.dialogflow.com/api-client/demo/embedded/28aa98b2-9d3a-40bb-b634-669618c517a9">
</iframe>
        
</body>
