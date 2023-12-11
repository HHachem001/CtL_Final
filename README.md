# [Vist the Tax Assistant Website](https://hhachem001.github.io/CtL_Final/Welcome.html)

## Basic Federal Income Tax Assistant 

Welcome to the Basic Federal Income Tax Course Website repository! This project is designed to assist users who are enrolled in a Basic Federal Income Tax course. It provides a range of features to enhance your learning experience, including quizzes, a chatbot to check your eligibility under specific IRS codes, and a searchable course notes outline with AI capabilities.

## Project Overview

The Basic Federal Income Tax Course Website aims to make learning about federal income tax more interactive and engaging. The website includes the following features:

- **Quizzes**: Take quizzes to test your knowledge of federal income tax concepts.

- **Chatbot**: Use the chatbot to ask tax-related questions.

- **Course Notes Outline**: Access a comprehensive course notes outline, which can be searched using a basic search tool or a search tool enhanced with AI features.

- **IRC Code Extractor**: Extract any Internal Revenue Code that is referenced in any document uploaded.

## Features

1. **Quizzes**:  
   - Interactive quizzes to help reinforce your understanding of federal income tax concepts.
   - Track your progress and view your scores.

2. **Chatbot**:
   - Ask questions related to taxes.
   - Receive instant responses and guidance.

3. **Course Notes Outline**:
   - Access detailed course notes organized by topics.
   - Search for specific content.

4. **IRC Code Extractor**:
   - Upload PDF of a case or article
   - Utilize RegEx to extract IRC Codes referenced in document

## Technologies Used

The project is built using the following technologies:

- **PDF Generation:** The Assistant utilizes the [PDFMake Library](https://pdfmake.github.io/docs/0.1/) for document generation, ensuring efficient and accurate document creation.
- **AI Utilization:** The project leverages the [Transformer.js AI library](https://github.com/xenova/transformers.js) for AI functionality, enhancing the user experience.
- - **PDF Extraction:** The project leverages the [Mozilla PDF.js library](https://mozilla.github.io/pdf.js/) for extracting IRC Code from uploaded documents.
- HTML
- CSS
- JavaScript
- PHP

## Current Known Issues in Version v12.023A

-A.I. Course Notes search feature is not handing off user prompt to the larger LLM
-IRC Code Extractor may not capture all Revenue Codes from the uploaded PDF
-Capital Gains calculator may has difficulty determining if there is a NSTCL or a NSTCG
-Feedback submitted by users is not forwarded to me, and it ends up in the "void" where it will never be read.
-Basic RegEx Chatbot is not as useful as the A.I. ChatBot, and it will be deprecated

  ## Acknowledgments

- **Creator:** The Basic Income Tax website and the A.I. Frontend was designed and created by Hashim Hachem.

- **Assistance:** Special thanks to GitHub Copilot for their assistance in the development process and for providing free access to the Copilot A.I.

