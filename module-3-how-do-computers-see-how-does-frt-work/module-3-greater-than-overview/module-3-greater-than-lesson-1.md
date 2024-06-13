---
description: Rich discussions, active listening, hands-on-learning
---

# Module 3 -> Lesson 1

{% hint style="info" %}
### Essential Question:

How do computers learn to 'see'?
{% endhint %}

### Anchor Text(s) for this Lesson

* [Computer Scientist Explains Machine Learning in 5 Levels of Difficulty](https://youtu.be/5q87K1WaoFI?feature=shared) | WIRED



### Supporting Text(s)/ Resources for this Lesson

* [**AI Teachable Machine**](https://youtu.be/3BhkeY974Rg) video introduction
  * [video transcript](https://docs.google.com/document/d/1y8jt8VypyovjQ2hrLk2thGCI\_orreSnFx6H7niE93Pg/edit?usp=sharing)
* [**Teachable Machine**](https://teachablemachine.withgoogle.com/v1/) an AI Experiment by folks from Google
* Sample slide deck: [<mark style="color:purple;">**Module 3 --> Lesson 1**</mark> ](https://docs.google.com/presentation/d/1I7BiazN5IikXRaYRtMoAIVADUzw1B5oJ6rMnQbVV87k/edit?usp=sharing)
* [**How Machines Learn** ](https://www.youtube.com/watch?v=R9OHn5ZF4Uo)by CGP Gray, YouTube, December 18, 2017
  * [video transcript](https://docs.google.com/document/d/1iRyx8IoSsEJGq0TIgZjzyjZY8WL8kyoNW-ymvEjp1TU/edit?usp=sharing)&#x20;
* Recommended reading/ viewing to dive deeper:
  * [**Face Detection & Recognition: How Machine Learning Approaches & Algorithms Make it Possible**](https://medium.com/nerd-for-tech/face-detection-recognition-how-machine-learning-approaches-and-algorithms-make-it-possible-4b5896aefb88) by Roger Brown, August 11, 2021, Medium \[[archived link](http://archive.today/uVtTt)]
  * [**The Coded Gaze**](https://drive.google.com/file/d/1s3hfuqItie\_DfanIq-KpcNmEY2nHHNXQ/view?usp=sharing) by Joy Buolamwini 📽 (recommended extension)

### Lesson Overview

In this lesson, students will briefly revisit the types of claims and evidence they gathered in Module 2 and how they related to issues of power that arise with the use of FRT for surveillance and policing. The focus is then shifted to inform students that in this module, they will be learning about how FRT works so they can make technical claims to support their position. Students will view part of a video, [Computer Scientist Explains Machine Learning in 5 Levels of Difficulty](https://youtu.be/5q87K1WaoFI?feature=shared), that explains how humans teach computers to 'see.' They will then experiment with an application called [Teachable Machine](https://teachablemachine.withgoogle.com/v1/). The big idea in this lesson is to understand that first a computer must detect a face and that we use machine learning to train computers to know what is a face and what is not a face.

### Nota Bene

For students who have previous exposure to computer science, whether in school or through independent study, you can offer them enrichment opportunities by inviting them to use the [original version of Teachable Machine](https://teachablemachine.withgoogle.com/train), which gives them more exposure to what is happening 'under the hood'--that is, they can see the model that developed after they train the machine with different images.&#x20;

### Objectives

Students will be able to...

* explain in general terms how humans teach computers to 'see.'
* train a machine by creating three distinct image classes.

### Suggested Duration

45 minutes (adjust according to your students' needs)

### NYS Next Generation ELA Standards

* **RST7:** Translate information expressed visually or mathematically into words.
* **RH9:** Compare and contrast treatments of the same topic in several primary and secondary sources.
* **RH7:** Integrate and evaluate visual and technical information (e.g., in research data, charts, graphs, photographs, videos or maps) with other information in print and digital texts.

### NYS Computer Science & Digital Fluency Standards

* **9-12.DL.2:** Communicate and work collaboratively with others using digital tools to support individual learning and contribute to the learning of others.
* **9-12.CT.10:** Collaboratively design and develop a program or computational artifact for a specific audience and create documentation outlining implementation features to inform collaborators and users.
* **9-12.IC.5**  Describe ways that complex computer systems can be designed for inclusivity and to mitigate unintended consequences.

### Vocabulary

* **machine learning**: a type of artificial intelligence in which computers use huge amounts of data to learn how to do tasks rather than being programmed to do them
* **artificial intelligence**: the study and development of computer systems that can copy intelligent human behavior
* **detect**: to discover or notice something, especially something that is not easy to see, hear, etc.
* **technical:** connected with the practical use of machinery, methods, etc. in science and industry
* **technical claim**: use technical information to make a statement about something that you will argue is true
* **facial detection**: technology that allows a computer to 'see' whether a face is in its view
* **facial recognition**: technology that allows a computer to identify a person by their face

### Hook

Present students with the following prompt to respond to independently in writing or in a small group conversation:

How do you think facial recognition technology works? From your perspective, should decision makers such as principals, mayors, or police chiefs be required to explain to the public how this technology works before implementing it? Explain your reasoning.&#x20;

### Mini-Lesson

Remind students that in the last few lessons they saw how power issues arise with the use of FRT for surveillance and policing purposes. Elicit from students examples they might remember from the Ovide and Kilgannon texts. Possible examples include: (potential?) abuse of power as demonstrated by the owner of Madison Square Garden's application of FRT; questions around how government should or should not exercise power in the form of regulations (Ovide article). Highlight for students that with the information gleaned from articles in the previous module, they were able to make claims that relate to power in some sense and how having or not having checks on that power is something to consider. Present the following claims and ask students to think/ talk about how power and checks on that power show up in each:

* FRT can be an effective tool for policing as long as it is properly regulated.
* FRT is an effective tool for policing.&#x20;
* FRT can be abused by people in positions of power.&#x20;

Inform students that in the next few lessons they are going to learn a bit about _how_ FRT works and some technical reasons it might NOT work as expected. Let students know that this will prepare them to make technical claims.&#x20;

First things first, computers must detect a face before they can try to determine whose face that is. So, how do humans teach computers to detect faces? Machine Learning!&#x20;

Play the video [How Machines Learn](https://www.youtube.com/watch?v=R9OHn5ZF4Uo) for students with the following purpose for viewing: What steps must computer scientists take to ensure that computers learn to detect all faces? Ask students to share their thoughts about this question as you debrief the video.  \[Here is another video about machine learning that you might want to use: [What is Machine Learning](https://www.youtube.com/watch?v=QghjaS0WQQU)]

### Activity

Let students know that they will now have an opportunity to train their computer to see using the Teachable Machine interface. You can show students this video, [AI Teachable Machine](https://www.youtube.com/watch?v=3BhkeY974Rg), which explains how the interface works. Then, have students work in groups of four to experiment with the Teachable Machine interface. Have students train the machine with three classes: each class should be pictures of one of the four student's face. The second class should be images of a second student's face and so on. The fourth student--whose face was not used in the training data--should then stand in front of the camera to see how the computer classifies their image.

Ask them to consider these questions: Why is it important to train more than one class when teaching a computer to see? What are some implications of this when we think about FRT?&#x20;

### Wrap Up

Highlight for students that when teaching a machine to 'see', it is necessary to train multiple classes, so the computer has both examples and non-examples, as in the video--this is a bee and this is a three--or, with face detection: this is a face and this is NOT a face. Let students know that in the next lesson, they will learn how machine learning is related to facial detection and facial recognition technologies.
