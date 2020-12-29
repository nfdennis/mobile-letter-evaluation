# mobile-letter-evaluation
Creating a react-native component for evaluating drawn letters and shape path objects on mobile devices. 

# Motivation
Help the sad kids around the world learn to draw the letter 'A' without having to use pen and paper. 

# Tech/Framework used
**Built with** 
  * React-Native

# Some Requirements
  1. Complete offline capability
  1. Scalable drawing canvas / scalable models for comparison
  1. Scoring rubric 
  1. Stroke order aware

# Character Evaluation

## Ideas

### Error based on furthest distance

- Compare each user stroke to the correct answer stroke and find the furthest distance from the goal
  - Rescale the drawn answer to the correct answer to compare
  - Compare the lines relative to the bounds

_Issues_

- Resizing, rotating, and repositioning could be error prone.

### Use existing OCR libraries

Can we use confidence metrics from the library to evaluate the characters?

- https://antimatter15.com/ocrad.js/demo.html
- https://tesseract.projectnaptha.com/
- https://kdzwinel.github.io/JS-OCR-demo/
- https://openbase.io/categories/js/best-nodejs-ocr-libraries?orderBy=RECOMMENDED&

# Features
  
# Code Example
  
# Installation

# API Reference

# How to use?

# Credits

# License 
