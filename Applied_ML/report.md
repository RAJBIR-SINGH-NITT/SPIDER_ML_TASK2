Applied ML Report: Healthcare Information Assistant
Introduction
This project is an Applied Machine Learning system designed to answer health-related questions using evidence retrieved from trusted medical sources. The goal is to build a reliable healthcare information assistant that provides grounded responses, source citations, and confidence information instead of behaving like a generic chatbot.
SPML_TASK_2-1.pdf

Objective
The objective of the system is to take a user query, retrieve the most relevant medical information, and generate a clear answer based only on the retrieved evidence. The system is also designed to communicate uncertainty, avoid unsupported claims, and support safe question answering for healthcare-related use cases.
SPML_TASK_2-1.pdf

Methodology
The project was developed in Google Colab. The workflow begins when the user enters a medical question, such as symptoms of diabetes or ways to lower high blood pressure naturally. The system then retrieves relevant information from trusted medical sources, generates a response grounded in that evidence, and displays the answer along with citations and confidence information when available.
SPML_TASK_2-1.pdf

Results
The system was tested with sample questions and produced structured answers with supporting source references. Example outputs show the question, the generated answer, and the confidence score, which demonstrates that the pipeline works end to end. Screenshots of these responses can be saved in the outputs/ folder for submission.
SPML_TASK_2-1.pdf

Architecture
The architecture of the system follows a simple pipeline: user input, retrieval of relevant documents, answer generation, citation display, and confidence estimation. This design supports evidence-based responses and makes the system easier to explain and evaluate. A block diagram of this flow should be included in the architecture/ folder.
SPML_TASK_2-1.pdf

Conclusion
This project demonstrates a practical Applied ML healthcare question-answering system built in Colab. It shows how retrieval-based answering, citations, and confidence reporting can be combined into a trustworthy assistant. The final submission should include the code, architecture diagram, report, outputs, and demo video link