# Chat_App_with_Langchain

Below is the actual link to Colab NB in case issue in GITHUB preview: 
https://colab.research.google.com/drive/1cpNLCudfUob8cuFY-Y42kGockzkT09xz?usp=sharing

# Introduction:
In this project we are creating a chat app using Langchain and OpenAI. 

Lets say you possess a PDF containing substantial textual content, and you're eager to extract data through query-based interaction. This tutorial aims to elucidate the process, allowing anyone to comprehend its implementation swiftly.

Following library installations—such as Langchain, OpenAI API, and PDF2—along with the requisite dependencies, like PyPDF2 and PyTorch, we proceed to import necessary modules.

The PDF reader facilitates text extraction from the PDF file. By enumerating through each page, we compile the raw text into a single variable. Subsequently, the text undergoes segmentation via the character text splitter, ensuring manageable chunks conducive for analysis. These chunks are then converted into embeddings using the OpenAI embeddings library.

With the text transformed into embeddings, we employ the Langchain's question-answering feature, facilitated by the OpenAI model, to respond to inquiries posed within the PDF content. By specifying the query and the input document, the model retrieves relevant information, showcasing its potential for insightful data extraction.

Through this methodology, one can seamlessly navigate through PDF documents, extracting valuable insights via straightforward queries. Whether it's delving into budgetary details or exploring thematic nuances, the Langchain coupled with OpenAI API presents a robust solution for text-based data interrogation.

In essence, this underscores the fusion of advanced technologies to streamline information retrieval processes, empowering users to harness the wealth of knowledge encapsulated within textual documents effortlessly.

# How to run in Colab:
1. Copy password generated in the second last cell.
2. Click on the link generated in last cell.
3. Enter the copied password into the website.
4. Add link of your PDF and press enter for next input.
5. Ask your query and enter for the answer.

# Example Output
<img width="1314" alt="Screenshot 2024-05-19 at 8 13 25 PM" src="https://github.com/bee20/Chat_App_with_Langchain/assets/13919602/77124784-d3ef-4339-9f77-a4cf6ca20e5f">

