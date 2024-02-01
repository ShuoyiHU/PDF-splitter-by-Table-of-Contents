# PDF-splitter-by-Table-of-Contents
This is a small tool to help people use python to split PDF file by the Table of Contents of the file. It is useful when people want to split a textbook or electronic book into several parts and save each part on softwares for note-taking.

<b>Guideline</b>
1. Download PyMuPDF in terminal.
    
    pip install PyMuPDF
2. Download and Open the pdfspliter.py code in this project. Either open with VScode etc. or directly run the code.
3. After check with your own pdf file about the depth of split that you want to have. Follow the instruction in the terminal, enter the name of the pdf file and the absolute path of it, the depth of the toc that you want to cut as an integer, the absolute path of the folder that you want to save the pdf files respectively.
4. Check the output folder for the result.

<b>Note on File Naming</b>

On my own testing computer, some special characters like \/:*?"<>| are not allowed to appear in a pdf file name, so in the processing process, these characters were intentionally removed.
If you need personalization in this step, please modify line 24 in the code. Or send me an e-mail (hushuoyi@westlake.edu.cn), I would be more than happy to help if you could give me the instruction on what kind of special characters are not allowed in other systems' setup.

<b>Tips</b>

Any problems or comments or advice? Contact me by sending an email to hushuoyi@westlake.edu.cn. I'm more than happy to answer these questions.