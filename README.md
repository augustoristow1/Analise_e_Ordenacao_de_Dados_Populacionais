This paper presents a comprehensive solution for reading, filtering, processing, and sorting population data from CSV files using Java. The proposed system is designed to identify the most populous country in 1960, while effectively filtering out irrelevant entries such as socioeconomic classifications (e.g., "Low income," "Middle income") and regional aggregates (e.g., "Europe & Central Asia"). The approach leverages the simplicity of the insertion sort algorithm to organize the data based on population figures, despite its inherent complexity of O(n²). Although insertion sort is not the most efficient algorithm for large datasets, its intuitive implementation and clarity make it a suitable choice for educational purposes and moderate-sized data files.
A central concept in this work is the Value Trace Problem, which refers to the challenge students face in understanding how variable values change dynamically during code execution, particularly when working with algorithms. This problem is addressed through the system's ability to trace variable states line-by-line, allowing users to visualize how data evolves throughout the execution of the code. This feature makes the system particularly valuable as a teaching tool, helping learners grasp fundamental concepts such as control flow, iteration, recursion, and data manipulation within Java programming.
The paper also discusses the potential for scaling the system by integrating more efficient sorting algorithms like MergeSort or QuickSort, which have a time complexity of O(n log n) and are more suitable for handling large datasets. Furthermore, we explore the advantages of utilizing specialized libraries, such as OpenCSV and Apache Commons CSV, which would provide greater flexibility and robustness when dealing with complex CSV files that contain quoted fields, multi-character delimiters, or embedded commas.
Results from the experiments conducted in classroom settings with computer science students show that the proposed system significantly enhances their understanding of algorithm behavior and the dynamic state of variables during execution. The system allows students to actively interact with the code, encouraging a hands-on approach to learning programming principles, and facilitating error detection through a clearer understanding of how algorithms function in real-time.
In conclusion, this work demonstrates that the Value Trace Problem can be effectively addressed through the development of an interactive system that provides real-time feedback on variable changes. While the insertion sort algorithm served as a starting point for introducing sorting techniques, the system has the potential to be expanded with more advanced algorithms and additional features, making it a versatile tool for both educational and practical applications. This solution not only improves the learning experience for programming students but also provides a foundation for future developments in automated learning systems and interactive programming environments.