## LLM4SocBeSci
The course introduces the use of open-source large language models (LLMs) from the Hugging Face ecosystem for research in the behavioral and social sciences. 

### Resources
```@misc{hussain_binz_mata_wulff_2023,
 title={A tutorial on open-source large language models for behavioral science},
 url={osf.io/preprints/psyarxiv/f7stn},
 publisher={PsyArXiv},
 author={Hussain, Zak and Binz, Marcel and Mata, Rui and Wulff, Dirk U},
 year={2023},
 month={Dec}
}
```
[Hugging face documentation](https://huggingface.co/docs)<br>
[Hugging face book](https://transformersbook.com/)

#### Installation Instrucitons
1. If you do not have a Google account, you will need to create one (this can be deleted after the workshop).
2. Navigate to Google Drive (https://drive.google.com/).
3. In the top-left, click New > More > Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps", 
search for 'Colaboratory', and install it. Then click New > More > Colaboratory.
4. Run the following code snipped in the first cell (```shift + enter```) of your notebook to mount your Google Drive to the Colab environment.
A pop-up will ask you to connect, click through the steps to connect your Google Drive to Colab (you will have to do this
every time you open a new notebook).
```
from google.colab import drive
drive.mount("/content/drive")
```
5. Clone the GitHub repository to your Google Drive by running the following code snippet in the second cell of your notebook:
```
%cd /content/drive/MyDrive
!git clone https://github.com/Zak-Hussain/LLM4SocBeSci.git
```
6. Go back to your Google Drive and navigate to the folder "LLM4SocBeSci". You should see the directories XX, XX, and XX 
containing the relevant notebooks (.ipynb files) and data (it may take  a couple of minutes for the files to appear).
7. Open the notebook for XX 
8. In the top-menu bar, click Runtime > Change runtime type > Hardware accelerator > T4 GPU
9. Run the first cell of the notebook to install the required packages. This may take a few minutes and ask for you to
give permission to access your Google Drive. 
You are now ready to start the exercises!