---
title: News
date: 2024-01-05 08:01:35 +0300
label:
image: '/images/newspage.png'
featured:
---
<title>Button Example</title>
<style>
  #output {
    width: 300px;
    height: 100px;
    border: 1px solid #ccc;
    padding: 10px;
    margin-bottom: 10px;
    font-size: 16px; /* Adjust the font size */
    font-family: Arial, sans-serif; /* Change the font family */
    line-height: 1.5; /* Adjust line height */
    resize: none; /* Disable resizing */
    outline: none; /* Remove outline */
  }
  .button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  .button:hover {
    background-color: #0056b3;
  }
</style>
</head>
<body>

<!-- Text box -->
<textarea id="output" placeholder="Text will appear here"></textarea>

<!-- Button -->
<button onclick="displayText()">Show Text</button>

<script>
function displayText() {
    // Get the text box element
    var textBox = document.getElementById("output");

    // Set the text to be displayed
    var textToShow = "Hello, world! This is the text to be displayed.";

    // Show the text in the text box
    textBox.value = textToShow;
}
</script>
</body>