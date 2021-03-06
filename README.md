<img align="left" src="https://user-images.githubusercontent.com/62319355/105017774-2307eb00-5a7f-11eb-94e6-4c22b2b6f77c.png" width="150" height="80" alt="SAP image">
<img align="right" src="https://user-images.githubusercontent.com/62319355/105784475-dad35600-5fb3-11eb-8dc2-eb61292af5bc.png" width="150" height="80" alt="SAP image">
:smile: :grinning: :sleepy: :relieved: :confused: :open_mouth: :astonished: :thumbsup:

## SAP-Excel Automation using Python
```
Hi,  my name is Ray Kim. I am here to share my experience in SAP automation. 
I am the furtherest thing from an expert but I hope my codes can help you.
You can contact me at rainmankim@gmail.com for further details.

This repository will explain how you can automate SAP log-in and execute T-code.
If you can do that, you can easily figure out the rest, using Stefan's recorder.
I am keeping things simple here to avoid confusion

In this use-case, I am not using PyAutoGui or OpenCV.
Those things can be used by all means.
But Stefan's recorder shortens development time for SAP automation at zero cost.
```


## Before starting, I recommend that you prepare two things
### (1) Ensure your scripting is enabled on your SAP.
<img align="center" src="https://user-images.githubusercontent.com/62319355/105824646-99659980-5ff9-11eb-9dcb-3cdbd9a4efbf.png" alt="SAP image">

#### You might need to request your IT department to allow this.
### (2) Download Stefan Schnell's SAP Script Recorder.
#### SAP has a built-in recorder. But if you use that you will need to change the syntax to be used in Python.
#### Using Stefan's Recorder generates Python-friendly syntax along with many other powerful features.
<img align="center" src="https://user-images.githubusercontent.com/62319355/105824768-c3b75700-5ff9-11eb-881c-f25490c59efd.gif" alt="Tracker image">
https://tracker.stschnell.de/



## Next, open any Python IDE/code editor. 
## I recommend Jupyter Notebook so that you can slice data in-action.
### Below is an example of recorded scripts which are modified to suit my needs (*for loops + various conditions)
<img align="left" src="https://user-images.githubusercontent.com/62319355/105824896-e9446080-5ff9-11eb-99ee-a6dee9965f80.png"  alt="Jupyter image">


## I have two main functions in my file — def sap_automate()  and def enter_data()
### sap_automate(df) is the main function that will establish connection/session and automate log-in
### enter_data(session,df) is a nested function that will execute actions within SAP
<img align="left" src="https://user-images.githubusercontent.com/62319355/105825093-26a8ee00-5ffa-11eb-8dab-626fc0b86062.png"  alt="Jupyter image">


## Dealing with Excel
### If you are writing to an existing excel, Pandas library would be not be enough
### Use Excel modules such as xlwings or xlsxwriter

## Credits
```
- Stefan Schnell
- SAP community (https://answers.sap.com/index.html)     
- https://guides.github.com/features/mastering-markdown/
- Secular saints of StackOverFlow
```


