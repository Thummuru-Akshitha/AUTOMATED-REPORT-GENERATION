# AUTOMATED-REPORT-GENERATION

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: THUMMURU AKSHITHA

*INTERN ID*: CT06WR252

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION OF AUTOMATED-REPORT-GENERATION*:

This Python program automates a complete workflow for creating, analyzing, and reporting sales data. It begins by generating a sample dataset containing the names of four salespersons, their corresponding sales figures, and the regions they belong to. This sample data is structured using a dictionary and then converted into a Pandas DataFrame. The DataFrame is saved to a CSV file named "sales_data.csv" so that the program always has some initial data to work with. Once the sample data is created, the program attempts to read the CSV file using Pandas. To make the program more robust, it employs error handling to gracefully catch cases where the file might not exist, providing a clear message if the file is missing. After successfully reading the data, the program moves on to analyzing it. In this step, it computes a set of descriptive statistics about the sales figures, such as the count of entries, mean, minimum, maximum, and quartile values, using the describe function. It also calculates the total and average sales separately to summarize the overall performance of the team. These pieces of information are important for understanding how sales are distributed and identifying any outstanding trends or outliers.

The final step of the program is to generate a PDF report summarizing the findings. Using the FPDF library, the program creates a professional-looking PDF titled "Sales Report". It includes the total and average sales figures, followed by a detailed breakdown of the statistical summary obtained earlier. Each piece of information is neatly formatted for easy reading. The use of a bold title, proper font settings, and organized structure makes the generated PDF suitable for sharing in a business environment. Once the report is created, it is saved as "sales_report.pdf", and the user is notified of the successful completion. The overall execution is controlled by a main() function that orchestrates the flow from data creation to reading, analysis, and report generation. Additionally, the script is wrapped in the if __name__ == "__main__" block to ensure that the main function runs only when the script is executed directly, not when it is imported as a module elsewhere.

This program is an excellent example of integrating data management, basic statistical analysis, and document generation in Python. It shows how a simple project can cover multiple important skills such as reading and writing files, handling exceptions, summarizing datasets, and creating formatted outputs like PDFs. It can be very useful for small businesses, students, or beginners looking to understand the real-world application of Python. Moreover, the modular structure, with separate functions for each logical part, makes the code clean, reusable, and easy to expand. Potential improvements could include adding graphs to the PDF, using more advanced styling, or dynamically loading different datasets based on user input. Overall, this program demonstrates how a simple set of tools can create a powerful, end-to-end automated reporting system.

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/0d8563fd-db19-4969-a144-d74f10ba0adf)
