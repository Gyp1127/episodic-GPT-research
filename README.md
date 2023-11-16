# Research Topic: Remembering Real World Events (LLMs)

## Research Inspiration ([Simon Dennis](https://findanexpert.unimelb.edu.au/profile/811247-simon-dennis)):
Where were you at 2pm last Thursday? Questions like these are important for us as individuals but also have significant consequence for eye witness testimony (Laliberte, Yim, Stone & Dennis, 2021) and for public health (e.g. covid contact tracing). We have collected data including images, locations, audio and accelerometry from participants over a period of month and subsequently asked them where they were. In this project, we will provide this data to a pretrained large language model and see whether it makes the same kinds of errors as people do.
Laliberte, E., Yim, H., Stone, B., & Dennis, S. J. (2021). The fallacy of an airtight alibi: Understanding human memory for “where” using experience sampling. Psychological Science, 32(6), 944-951.

---

## Dataset
Consists of two files from Mackenzie (2019). 

- The *event.csv* file lists different types of information regarding all the participants' current state in intervals. The information includes spatial information, temporal information, and emotions. 
- The *experiment.csv* file lists all the questions in the experiment that was conducted. Each entry lists which participant it belongs to, what they responded to, whether they were correct and keys to link the questions to the specific event entries.

## GPT Scripting
*Filename: gpt_remembering_events.ipynb*
The program takes the data from the *event file* & *experiment file* to reverse-engineer the questions that were asked to the participants. The events that a particular participant experienced are fed to a large-language model (GPT3.5 Turbo). Subsequently, the questions are provided sequentially and the output is saved.

## Data Analysis
*WIP*
