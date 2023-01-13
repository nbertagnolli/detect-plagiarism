# Spot Plagiarism

This repostiory holds some very simple javascript for detecting if a given writing sample came from a human or a Large Language Model (LLM) like ChatGPT.  Please visit [www.spotplagiarism.com](www.spotplagiarism.com) to interact with the application.

# Design
The system was built to run client side.  I wanted to try and approach the problem of identifying machine text in a way that would be easy to host and cheap to maintain.  The system works by using a quantized version of DistilGPT to calculate the perplexity of a given input text.


# Blog post on the model coming soon


If you like this and aren't a teacher (I don't want coffee from teachers thank you for your service :).
<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="nbertagnolli" data-color="#FFDD00" data-emoji="" data-font="Cookie" data-text="Buy me a coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#ffffff" ></script>