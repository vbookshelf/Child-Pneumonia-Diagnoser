
Live Web App: 

This is a prototype for a freely available online tool that can look at a chest x-ray and almost instantly tell if a child has pneumonia, and if so, if it is viral or bacterial pneumonia. The model was trained on chest x-rays of children aged from 1 to 5. From the results, the model seems to be quite good at detecting whether or not a child has pneumonia. However, it also seems to be more sensitive to detecting bacterial pneumonia than viral pneumonia. According to Google, in bacterial pneumonia there will be a much more visible presence of fluid in the lungs than in viral pneumonia. So maybe the model is detecting signs of fluid. I don't know. Because bacterial pneumonia is more serious than viral pneumonia, I decided not to try to change this tendency.

The process used to build and train the model is described in this Kaggle kernel:<br>

The dataset used for the training can be found here:<br>

All javascript, html, css and python files used to create the web app are freely available in this repo. [Coming Soon]

Similar to my skin-lesion-analyzer app, I have no way of testing this app in practice. So I'll just leave it to roam the vast expanse of the internet. Adios.

