# tExtractor
The code in this repository extracts text from pdf/picture/scanned documents using the following methods.

OCR (Optical Character Recognition) technique: used to identify words in a picture/scanned document and convert it into machine-readable text, that can be processed further. Although the technology is mature and uses advanced techniques, it can often produces an output that is incorrect or ridden with irrelevant pieces.

## Steps to run the program:

   1. Clone the repository using:
    
         > git clone https://github.com/akshaygona/textractor.git
        
2. Please go to [pdftoimage.com](https://pdftoimage.com/) to convert the pdf file to jpg image.

3. We need to place the pdf and the correponding images in ___/data/demo___ folder.

4. Now, run the demo.py file.

5. Result can be seen on the command line(for windows users) or terminal(for Ubuntu users).
      * Note: Please remove the files previously being compiled in the ___/data/demo___ and ___/data/result__ folder.
      
 # Results
 * Localized text proposals on a pdf.
 * Bounding box co-ordinates can be found in data/results/*.txt .
