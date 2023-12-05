# Paraphraser

This task involves creating a paraphrasing prompt for OpenAI's GPT-3.5-turbo model. The user is required to input a text paragraph, choose an output tone (Academic, Creative, Aggressive), and select an output length (1x, 2x, 3x). The result is a list of paraphrased sentences presented in a JSON format.

Usage:

Input Text Paragraph:
The paragraph that you want to be paraphrased.

Output Tone:
Choose from Academic, Creative, or Aggressive.

Output Length:
Select the desired length (1x, 2x, or 3x).


# Chatbot QnA

This task involves building a chatbot that can answer questions about a specified researcher using information from their Google Scholar page.

Usage:

You can ask questions such as:
What are the most influential papers by this author?
How many papers did the author publish in the last year?
What are the takeaways from those papers?
Who are the coauthors of the researcher?

Providing Researcher Information:

The chatbot relies on the researcher's information from their Google Scholar page.

Note:

This chatbot is designed to answer questions about any researcher. The information is fetched dynamically from the researcher's Google Scholar page.

# Answer with Citation

This task involves generating answers with citations based on given contexts from research papers. The user provides a question and multiple contexts (author and text from research papers).

Usage:

Provide Question:
Input the question you want to be answered.

Provide Contexts:
For each context, provide the author and text from research papers.

# Conversational Retrieval Chatbot (chatgpt.py)

This program utilizes OpenAI's GPT-3.5-turbo model to build a conversational retrieval chatbot. The chatbot can answer questions based on a provided dataset using a conversational retrieval approach.

## Purpose

This program was created for two specific reasons:

1. **Resume Evaluation:**
   - The primary purpose is to assist a friend in tracking, scoring, and selecting the best resumes for consulting roles. The chatbot can analyze resumes, flagging relevant skills and keywords to streamline the resume evaluation process.

2. **Trademark Search:**
   - Additionally, the program serves the needs of my friend who is an associate in one of the country's leading law firms. It enables the associate to upload large files and employ ChatGPT to search through them. The chatbot identifies instances where certain trademarks are used and flags these occurrences for further review.
