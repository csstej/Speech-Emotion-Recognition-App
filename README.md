# Speech-Emotion-Recognition-App
A Speech emotion Recognition Application made in FLASK which detects emotion in audio input.


Developped a speech emotion recognition platform to analyze the emotions of speakers.

We analye vocal emotions, using mostly deep learning based approaches. We deployed a web app using Flask :

![image](/Presentation/homepage.jpeg)

The tool can be accessed from the WebApp repository, by installing the requirements and launching `main.py`.


## Table of Content :
- [I. Context](https://github.com/csstej/Speech-Emotion-Recognition-App/blob/master/README.md#i-context)
- [II. Data Sources](https://github.com/csstej/Speech-Emotion-Recognition-App/blob/master/README.md#ii-data-sources)
- [III. Output](https://github.com/csstej/Speech-Emotion-Recognition-App/blob/master/README.md#iii-output)


In this project, we are exploring state of the art models in multimodal sentiment analysis. We have chosen to explore sound inputs and develop a model that gathers the information and displays it in a clear and interpretable way.

## 0. Technologies

![image](/Presentation/techno.png)

## I. Context

Affective computing is a field of Machine Learning and Computer Science that studies the recognition and the processing of human affects.
Speech Emotion Recognition is a relatively new discipline that aims to include sound. This field has been rising with the development of social network that gave researchers access to a vast amount of data.


## II. Data Sources
We have chosen to diversify the data sources we used depending on the type of data considered. All data sets used are free of charge and can be directly downloaded.
- For the text input, we are using the **Stream-of-consciousness** dataset that was gathered in a study by Pennebaker and King [1999]. It consists of a total of 2,468 daily writing submissions from 34 psychology students (29 women and 5 men whose ages ranged from 18 to 67 with a mean of 26.4). The writing submissions were in the form of a course unrated assignment. For each assignment, students were expected to write a minimum of 20 minutes per day about a specific topic. The data was collected during a 2-week summer course between 1993 to 1996. Each student completed their daily writing for 10 consecutive days. Students’ personality scores were assessed by answering the Big Five Inventory (BFI) [John et al., 1991]. The BFI is a 44-item self-report questionnaire that provides a score for each of the five personality traits. Each item consists of short phrases and is rated using a 5-point scale that ranges from 1 (disagree strongly) to 5 (agree strongly). An instance in the data source consists of an ID, the actual essay, and five classification labels of the Big Five personality traits. Labels were originally in the form of either yes (‘y’) or no (‘n’) to indicate scoring high or low for a given trait.
- For audio data sets, we are using the **Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)**. This database contains 7356 files (total size: 24.8 GB). The database contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. Each expression is produced at two levels of emotional intensity(normal, strong), with an additional neutral expression. All conditions are avail-able in three modality formats: Audio-only (16bit, 48kHz .wav), Audio-Video(720p H.264, AAC 48kHz, .mp4), and Video-only (no sound).” https://zenodo.org/record/1188976#.XCx-tc9KhQI
- For the video data sets, we are using the popular **FER2013** Kaggle Challenge data set. The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The data set remains quite challenging to use, since there are empty pictures, or wrongly classified images. https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

## III. Output

![image](/Presentation/bargraph.jpeg)

We get a histogram plot of the various emotions portrayed by the speaker and a remark.

