---
layout: default
---

### Background

The task is to identify expressions of candy speech („Flausch“) in online posts (YouTube comments).
We define candy speech as an expression of positive attitudes in social media toward individuals or their output (videos, comments, etc.).
The purpose of candy speech is to encourage, cheer up, support and empower others. 
It can be viewed as the counterpart to hate speech, as it also aims to influence the self-image of the target person or group, but in a positive way.


### Motivation

Numerous methods have been developed for detecting and censoring negative speech (e.g., hate speech or offensive or harmful language) on social media platforms. 
However, there is much less focus on identifying and promoting positive supportive discourse in online communities. Our shared task aims to address this gap and encourage researchers to focus on such positive expressions.

### Task Details

Candy speech detection is the task of identifying the presence of candy speech (at the span level) in a given YouTube comment thread and classifying each expression in one of the predefined categories. 
This shared task focuses on German speaking YouTube communities. Participants will be provided with a dataset of YouTube comments manually annotated for different types of candy speech expressions. 

The shared task includes the two following subtasks:

#### Subtask 1: Coarse-Grained Classification
The goal of this task is to identify whether the given comment contains candy speech or not. The dataset is manually annotated for the presence of candy speech (binary classification task).

#### Subtask 2: Fine-Grained Classification
The goal of this subtask is to identify the span of each candy speech expression in a given text and classify it in one of the predefined categories. The dataset is manually annotated for ten different types of candy speech expressions, such as "positive feedback", "compliment", "group membership" etc.


### Data

We will provide the participants with annotated training (and development) and unlabeled test datasets containing complete written, German language comment threads under YouTube videos posted by different content creators. 
The content creators and communities vary in topic, style, age group, etc. 
The test data and training data do not overlap wrt. to the original content creator of the video – the communities commenting on the videos can therefore be expected to differ.


#### Sample Data

 
<table>
<thead>
<tr class="header">
<th>YouTube comment</th>
<th>Candy speech (Subtask 1)</th>
<th>Candy speech type (Subtask 2)</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">hahahahah voll cool . der lehrer hat auswehrsehen das video angeklickt war voll geil</td>
<td markdown="span">yes</td>
<td markdown="span">positive feedback [hahahahah voll cool],[war voll geil]</td>
</tr>
<tr>
<td markdown="span">lehrer neven ganz übel ich beebde den unterricht ( facepalm )</td>
<td markdown="span">no</td>
<td markdown="span"> </td>
</tr>
<tr>
<td markdown="span">cool wie immer . Macht weiter so :)</td>
<td markdown="span">yes</td>
<td markdown="span">positive feedback [cool wie immer]; encouragement [Macht weiter so :)]</td>
</tr>
<tr>
<td markdown="span">+ Lu Spindler ran an die Sportklamotten ! 😁</td>
<td markdown="span">no</td>
<td markdown="span"> </td>
</tr>
<tr>
<td markdown="span">Omg 😍 omg 😍 omg 😍 das video ist einfach so shönn geworden aww deine augen sind so sc Hönn 😍 😍 ich liebe diich und deine videos yoh sehr ❤ love you LuNa 😍 😘</td>
<td markdown="span">yes</td>
<td markdown="span">positive feedback [Omg 😍 omg 😍 omg 😍], [das video ist einfach so shönn geworden]; compliment [aww deine augen sind so sc Hönn 😍 😍]; positive feedback/affection declaration [ich liebe diich und deine videos yoh sehr ❤]; affection declaration [love you LuNa 😍 😘]</td>
</tr>
</tbody>
</table>


### Important dates

- [Trial data](/data/trial/trial-data.md) available: February 15, 2025
- [Training data](/data/training/training-data.md) available: March 3, 2025
- [Test data](/data/test/test-data.md) available: May 17, 2025
- Evaluation start: June 16, 2025
- Evaluation end: June 27, 2025
- Paper submission due: July 11, 2025
- Camera ready due: August 15, 2025
- GermEval workshop: September 8-12, 2025 (co-located with KONVENS)


All deadlines are 23:59 UTC-12 (["anywhere on Earth"](https://en.wikipedia.org/wiki/Anywhere_on_Earth))


### Organizers

- [Yulia Clausen](), Ruhr-Universtität Bochum, Germany
- [Tatjana Scheffler](http://staff.germanistik.rub.de/digitale-forensische-linguistik/), Ruhr-Universtität Bochum, Germany
- [Michael Wiegand](https://homepage.univie.ac.at/michael.wiegand/), Universität Wien, Austria

__Contact:__ <germeval-2025-candy-speech@ruhr-uni-bochum.de> 
 

 
