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