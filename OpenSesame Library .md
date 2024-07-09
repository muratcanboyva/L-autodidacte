# Open Sesame Battery v1.0 - l'Autodidacte
## <span style= "color: #5475B8  "> What you can do with the experiments in this library?
_In this library, you will find a set of experiments that are frequently used and widespread in the field of cognitive neuroscience.  Under the relevant categories, such as Memory, Attention, etc., you will see various experiments. If you wish, you can run these experiments through a browser or download them to you computer and run on [OpenSesame Software][OpenSesame software]_
### <span style= "color: #5475B8  "> Content of the library
|Cognitive Function|Experiment|Modality
|------------------|----------|-------|
|Memory|N-back Tets|Visual|

# <Span style="color: #5475B8  "> **Memory**

## <Span style="color: #5475B8  "> *Working Memory*

### <Span style="color: #5475B8  ">N-BACK TASK 

In this OpenSesame experiment file, you'll find a N-2 Task based on [Kane et al. (2007)].

You can download the [experiment file].
### <Span style="color: #5475B8  ">N-2 Back Task Description

In this task, participants are presented with a sequence of letters, each displayed one at a time. The task involves monitoring these letters and identifying targets based on their position relative to previously presented letters. Specifically:

- **Letter Set**: The task utilizes a set of 8 unique letters.
- **Presentation**: Each letter from this set is presented 6 times within a single block and each letter is being used as target once.
- **Targets**: Approximately 17% of the letters are targets. A target letter is one that matches the letter presented two positions back in the sequence (n-2).
- **Non-targets and Foils**: The remaining letters are non-targets and foils. Non-targets are letters that do not match the letter presented two positions back. Foils are a special type of non-target; they are letters that match the letter presented one position back (n-1), but not the letter two positions back (n-2).

Participants are required to respond when they identify a target letter and withhold their response for non-targets and foils. The task is designed to assess working memory and attention by requiring the tracking of letter sequences and the identification of specific patterns.


Participants will receive a green fixation point when they respond correctly to N-2 targets, and a red fixation point when they do not respond to n-2 targets and/or respond to non-targets or foils.
## <Span style="color: #5475B8  "> Experiment File 
The opensesame experiment works with "Osweb" extension and uses JATOS system. JATOS is a system for managing online experiments. It allows you to create accounts for experimenters, upload experiments, and generate links that you can distribute to participants.
You can visit [here] to find extensive information on how to use JATOS system 


When you download the experiment file, you can open the file with the OpenSesame software on your computer. When you open the file, you will see that the Experiment consists of two loops. The first loop is the practice loop, the other loop is the experiment loop. While creating the experiment, OpenSesame's graphical interface was used and it was equipped with inline javascript elements to run smoothly via the osweb extension.
You can read the function of each piece of code in the comments section above the code by browsing through the inline javascript (JS) items in the experiment file. In Javascript, comments start with two slashes, for example; 

> // _This is a comment_

## <span style= "color: #5475B8  "> Support & Forum
You can find information on everything about in [OpenSesame Forum]. 

 :bulb: Also, now you can subscribe to OpenSesame's chatbot [Sigmund], Introducing a state-of-the-art general-purpose chatbot, uniquely equipped to excel in answering questions about OpenSesame and DataMatrix with unmatched precision. Users can choose from their favorite language models, including OpenAI GPT-4, Anthropic Claude 3, or Mistral Large, ensuring a personalized experience. Conversations are secure, with messages and attachments encrypted to maintain privacy. The chatbot also offers basic Python and R execution abilities, enabling users to perform simple programming tasks directly within the chat. Additionally, it provides the capability to search for scientific articles via Google Scholar and supports the upload and download of attachments, making it an invaluable tool for researchers and professionals alike.




[Kane et al. (2007)]: https://pubmed.ncbi.nlm.nih.gov/17470009/
[OpenSesame software]: https://osdoc.cogsci.nl/4.0/download
[experiment file]: https://www.muratcanboyvadaoglu.com
[here]: https://osdoc.cogsci.nl/3.3/manual/osweb/jatos/
[OpenSesame Forum]: https://forum.cogsci.nl
[Sigmund]: https://sigmundai.eu/login


_OpenSesame 4.0.27 Melodramatic Milgram Copyright Sebastiaan Mathôt 2010-2024_