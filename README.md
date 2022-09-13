# DLMAINLPCV01
NLP and Computer Vision
===

This repository represents notebooks for **N**atural **L**anguage **P**rocessing (NLP) and **C**omputer **V**ision as addition to the course book  "NLP and Computer Vision".<br> Following table gives an overview about the available notebooks.
The notebooks can be explored in a google [colaboratory](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index) environment.

Table of content
---
* NLP

|task | chapter |  library | notebook|     |
|-----|---------|----------|---------|-----|
|Regular Expressions| 1.2 | [Python standard library - ``re`` module](https://docs.python.org/3/library/re.html)| [notebook](notebooks/nlp_1-2_regexp.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_1-2_regexp.ipynb)| 
|Bag of Words| 1.3 | [Python standard library](https://docs.python.org/3/library/) | [notebook](notebooks/nlp_1-3_bag_of_words.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_1-3_bag_of_words.ipynb)| 
| Word Vectors| 1.3 | [Python standard library - ``re`` module](https://docs.python.org/3/library/re.html), [numpy](https://numpy.org/doc/stable/user/quickstart.html) | [notebook](notebooks/nlp_1-3_word_vectors.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_1-3_word_vectors.ipynb)| 
|Word Sense Disambiguation| 1.5 | [``pywsd``](https://pypi.org/project/pywsd/), [``nltk``](https://www.nltk.org/), [``wordnet``](https://pypi.org/project/wn/)| [notebook](notebooks/nlp_1-5_word_sense_disambiguation.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_1-5_word_sense_disambiguation.ipynb)|
|Named Entity Recognition| 1.6 |[``spaCy``](https://spacy.io/), [``simpletransformers``](https://simpletransformers.ai/about/)| [notebook](/notebooks/nlp_1-6_named_entity_recognition.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_1-6_named_entity_recognition.ipynb)|
|Part of Speech Tagging| 1.6 |[``spaCy``](https://spacy.io/)| [notebook](notebooks/nlp_1-6_part_of_speech_tagging.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_1-6_part_of_speech_tagging.ipynb)|
|Tokenization| 1.6 |[``spaCy``](https://spacy.io/)| [notebook](notebooks/nlp_1-6_tokenization.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_1-6_tokenization.ipynb)|
|Question Answering| 2.1 |[``transformers``](https://huggingface.co/docs/transformers/index)| [notebook](notebooks/nlp_2-1_question_answering.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_2-1_question_answering.ipynb)|
|Text Summarization| 2.1 |[``spaCy``](https://spacy.io/), [``pytextrank``](https://derwen.ai/docs/ptr/)| [notebook](notebooks/nlp_2-1_text_summarizaion_spaCy.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_2-1_text_summarizaion_spaCy.ipynb)|
|Topic Identification (Supervised)| 2.1 |[``simpletransformers``](https://simpletransformers.ai/about/)| [notebook](notebooks/nlp_2-1_topic_identification_supervised.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_2-1_topic_identification_supervised.ipynb)|
|Topic Identification (Unsupervised)| 2.1 |[``nltk``](https://www.nltk.org/), [``wordnet``](https://pypi.org/project/wn/)| [notebook](notebooks/nlp_2-1_topic_identification_unsupervised.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_2-1_topic_identification_unsupervised.ipynb)|
|Sentiment Analysis| 2.2 | [``simpletransformers``](https://simpletransformers.ai/) |[notebook](notebooks/nlp_2-2_sentiment_analysis.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_2-2_sentiment_analysis.ipynb)|
|Machine Translation| 2.4 | [``PyTorch``](https://pypi.org/project/torch/) | [notebook](notebooks/nlp_2-4_machine_translation.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_2-4_machine_translation.ipynb)|
|Chatbot| 2.5 | [rasa](https://github.com/RasaHQ/rasa-demo) | [notebook](notebooks/nlp_2-5_chatbot_RASA.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/nlp_2-5_chatbot_RASA.ipynb)|

* Computer Vision


|task | chapter |  library | notebook|     |
|-----|---------|----------|---------|-----|
|Basic Commands With OpenCV| 3 | [OpenCV](https://opencv.org/)| [notebooks](notebooks/cv_basic_commands.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_basic_commands.ipynb)| 
|Camera Calibration| 3.4 |[OpenCV](https://opencv.org/)| [notebook](notebooks/cv_3-4__camera_calibration.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_3-4__camera_calibration.ipynb)|
|3D Reconstuction| 3.5 |[OpenCV](https://opencv.org/) | [notebook](notebooks/cv_3-5_3D_reconstruction.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_3-5_3D_reconstruction.ipynb)|
|Filters| 3.6 |[OpenCV](https://opencv.org/)| [notebook](notebooks/cv_3-6_convolution_filters_OpenCV.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_3-6_convolution_filters_OpenCV.ipynb)|
|Image Classification and Evaluation <br> motion tracking| 4.1 | [PyTorch](https://github.com/pytorch/pytorch)| [notebook](notebooks/cv_4-1_image_classification_start.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_4-1_image_classification_start.ipynb) |
|Motion Tracking| 4.1 | [PyTorch](https://github.com/pytorch/pytorch)| [notebook]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
|Semantic Image Segmentation| 4.2 | [tensorflow](https://www.tensorflow.org/)<br>[keras](https://keras.io/) | [notebook](notebooks/cv_4-2_semantic_image_segmentation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_4-2_semantic_image_segmentation.ipynb)|
|Object Identification and Object Tracking| 4.3 | [YOLO](https://github.com/ultralytics/yolov3) <br> [Detectron2](https://github.com/facebookresearch/detectron2) <br> [PyTorch](https://github.com/pytorch/pytorch)| [notebook](notebooks/cv_4-3_object_detection.ipynb) <br> [notebook](notebooks/cv_4-3_objectDetection_Detectron2.ipynb) <br> [notebook](notebooks/cv_4-3_PyTorch_Object_Tracking.ipynb)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_4-3_object_detection.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_4-3_objectDetection_Detectron2.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iubh/DLMAINLPCV01/blob/master/notebooks/cv_4-3_PyTorch_Object_Tracking.ipynb)|
|Face Detection <br> Face Recognition| 4.4 |[facenet]() <br> [DeepFace]()| link to file|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
|Privacy and Security | 4.5 | [***library***]() | link to file |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
