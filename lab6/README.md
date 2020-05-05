## LAB 6 Summarization


Task: Automatically build abstracts of text documents.

Input: An array of texts in JSON format. Sample texts are at example_texts.json.

Output: An array of abstracts in JSON format (the order of abstracts corresponds to the order of texts in the input data).

The maximum size of each of the abstracts is 300 characters (including white space). If the size of the abstract exceeds the specified threshold, then only the first 300 characters will be evaluated. A trivial solution (the first 300 characters of the document) is allowed, but not welcome.

You can briefly describe the solution in the first line of the download file after the # character. The information will be useful to the authors of the course to gain an idea of the methods and approaches used.

Rating: ROUGE-2 - proximity to a set of manually compiled abstracts based on bigrams of words (value from 0 to 1).

Input can be found at dataset_43428_1.txt

Output is at outdataset_43428_1.txt
