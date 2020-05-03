Your task is to determine the tonality of the text on a scale of 1 (negative) to 10 (positive).
Input: texts separated by newlines (\ n).
Conclusion: for each text from the input, derive a tonal score from 1 to 10. The separator between the conclusions for different texts is the line feed (\ n).

For training, you can use a collection of texts and their corresponding grades. The training collection file corresponds to the input format, the grades file corresponds to the output format; encoding - UTF-8.

The square root of the root mean square error (Root Mean Squared Error) is used as an estimate.

You can briefly describe the solution in Read.me file at lab folder. The information will be useful to the instructor of the course in order to gain an idea of the methods and approaches used. Notebook must contain classification report, namely the comparison between the output of classificator and target var.
Sample Input:

По сравнению с предыдущими произведениями гораздо слабее. Хотя динамика событий осталась, но сама идея и ее воплощение...... Очень жаль.
Это просто СУПЕР... Давно ничего подобного не читала.
Sample Output:

2
8
