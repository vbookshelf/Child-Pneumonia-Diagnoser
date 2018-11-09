
Live Web App: http://child.test.woza.work/

This is a prototype for a freely available online tool that can look at a chest x-ray and almost instantly tell if a child has pneumonia. It can also tell if it is bacterial or viral pneumonia.

The model was trained on chest x-rays of children aged 1 to 5. From the results, the model seems to be quite good at detecting whether or not a child has pneumonia. However, it also seems to be more sensitive to detecting bacterial pneumonia than viral pneumonia. According to Google, in bacterial pneumonia there will be a much more visible presence of fluid in the lungs than in viral pneumonia. So maybe the model is detecting signs of fluid. I don't know. Because bacterial pneumonia is more serious than viral pneumonia, I decided not to try to change this tendency.

The process used to build and train the model is described in this Kaggle kernel:<br>
https://www.kaggle.com/vbookshelf/child-pneumonia-diagnoser-mobilenet/notebook?scriptVersionId=7216831

The dataset used for the training can be found here:<br>
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

All javascript, html and css files used to create the web app are available in this repo.

Similar to my skin-lesion-analyzer, I have no way of testing this app in practice. Adios.

