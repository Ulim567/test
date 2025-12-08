# 📸 VIDEX

**VIDEX** is a **semantic video indexing** system that converts **surveillance footage** into searchable segments through integrated **object detection**, **open-vocabulary expansion**, and **retrieval-enhanced scene captioning**. The system enables **rapid natural-language retrieval** of incident-relevant scenes and **reduces analytical workload** through **scalable distributed inference**.<br/><br/>

## 🗝️ Key word

- Semantic video indexing
- Natural-language video retrieval
- Surveillance video
- Open-vocabulary detection<br/><br/><br/>



# 📹 Demo Video

Demo video is avaiable in [YouTube](https://youtu.be/5DjljvfGSZQ)
<br/><br/>
  
  
# 🪄 Interface

The frontend of VIDEX offers user-friendly interface so that user can easily explore the result of analysis. Here are more detailed descroption about interface and how to use them.<br/><br/>
  
  
## 🏠 Home Page

<img src="Frame 64.png" width="500" />

<img src="Frame 63.png" width="500" />

- Create project by uploading video which want to analyze
    - Set project name and crop the video in upload modal
- Sort the project
- Search the project names
- Delete created projects<br/><br/>
  
  
## 📁 Project Page

<img src="Frame_55.png" width="500" />

- **Video Player**
    - Video w/ Yolo&OWL-ViT Object Detection Bounding Box
    - Play/Pause, Fast Forward, Volume Control, Full Screen
- **Anomaly Score Graph**
    - Show **LOF score** computed by video segment embedding
- **Search Panel**
    - Submit user query through Search Bar
    - Retrieve the top-20 description and correcponding timestamp
    - Combine consequtive similar description<br/><br/>
  
  
<img src="Frame_56.png" width="500" />

- **Object Confidence Graph**
    - Show multiple confidences of detected objects
    - User can toggle each object class graph
- **Object Detection Panel**
    - Show the result of object detection with thumbnail and correcponding timestamp
    - Filter the result by toggling chips or select and setting confidence threshold<br/><br/>
  
