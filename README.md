# secNB_SMS_Bigrams
Secure Naive Bayes SMS Bigrams (training and classification)
The source code for the original and the improved secure training and classification algorithms based on Naive Bayes over the SMS spam data collection dataset.
1) At the Source.cpp file comment out the #define POLYSWITCH to get the source code which was used for experimentation purposes of the journal paper:
   Kjamilji, Artrim, Erkay Savaş, and Albert Levi. "Efficient Secure Building Blocks With Application to Privacy Preserving Machine Learning Algorithms." IEEE Access 9 (2021): 8324-8353.
2) If the pre-processing identifier POLYSWITCH is defined (i.e. if the line #define POLYSWITCH is left uncpmmented at the Source.cpp file), 
   then it is the improved versions of 1) used for experimental purposes of the journal paper:  
   Kjamilji, Artrim, Erkay Savaş, and Albert Levi, "Blockchain assisted secure feature selection, training and classifications in distributed edge IoT environments"
 
Link to the paper(s):
1) https://ieeexplore.ieee.org/document/9314152
2) TBS

Video presentation(s) of the paper:
1) https://www.youtube.com/watch?v=4d3G5AmfbHU&list=PLN2gEfNq4GvfUYJx1aBE7R8bIAXt4JK2P&index=1
2) TBD

Open the solution using Visual Studio 2017. Set the SEALExamples as the start-up project. The implementation uses Microsoft's SEAL library v3.2 found in https://github.com/microsoft/SEAL
For better communication and computation costs (performances), run the code in Release mode. 

For any inqueries you can contact me by artrimq@gmail.com or artrimk@sabanciuniv.edu
