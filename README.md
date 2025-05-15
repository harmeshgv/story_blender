Yes! You can find movie scripts from these sources:  

1. **IMSDb (Internet Movie Script Database)** – [https://www.imsdb.com](https://www.imsdb.com)  
2. **SimplyScripts** – [https://www.simplyscripts.com](https://www.simplyscripts.com)  
3. **Script Slug** – [https://www.scriptslug.com](https://www.scriptslug.com)  
4. **Drew’s Script-O-Rama** – [http://www.script-o-rama.com](http://www.script-o-rama.com)  
5. **The Daily Script** – [http://www.dailyscript.com](http://www.dailyscript.com)  
6. **GitHub Repositories** – Search for “movie scripts dataset” on GitHub  
7. **Kaggle** – Search for “screenplay dataset”  

Would you like help in extracting structured data from these scripts? 🚀

To enable a model to understand and generate stories based on movie scripts, you'll need to extract several key types of data from the scripts. These data points will help the model grasp the narrative structure, character dynamics, and thematic elements of the stories. Here's a breakdown of the essential data you should aim to extract:

1. **Plot Structure**:
   - **Key Events**: Identify major plot points, such as the introduction, climax, and resolution. This helps the model understand the narrative arc.
   - **Scene Descriptions**: Extract descriptions of settings and actions to provide context for the story.

2. **Character Information**:
   - **Character Names and Roles**: Use Named Entity Recognition (NER) to identify characters and classify them into roles (e.g., protagonist, antagonist, sidekick).
   - **Character Traits**: Analyze dialogue and actions to infer character traits and motivations.

3. **Dialogue**:
   - **Speech Patterns**: Capture the style and tone of each character's dialogue to maintain consistency in character voice.
   - **Interactions**: Identify key interactions between characters to understand relationships and dynamics.

4. **Themes and Motifs**:
   - **Recurring Themes**: Use topic modeling or keyword analysis to identify central themes and motifs in the script.
   - **Symbolism**: Note any symbolic elements that contribute to the story's deeper meaning.

5. **Tone and Style**:
   - **Sentiment Analysis**: Determine the overall tone of the script (e.g., comedic, dramatic, suspenseful) using sentiment analysis.
   - **Stylistic Elements**: Analyze the writing style, including sentence structure and use of literary devices.

6. **Setting and World-Building**:
   - **Location Descriptions**: Extract details about the setting to provide a backdrop for the story.
   - **World Rules**: Identify any unique rules or elements of the story's world (e.g., magic systems, futuristic technology).

7. **Conflict and Resolution**:
   - **Central Conflict**: Determine the main conflict driving the plot and how it is resolved.
   - **Subplots**: Identify any secondary plots that add depth to the story.

8. **Genre-Specific Elements**:
   - **Genre Conventions**: Note any elements specific to the genre (e.g., horror tropes, romantic plot devices) to guide the model in generating genre-appropriate content.

By extracting these data points, you can provide a comprehensive understanding of the movie script to the model. This information will help the model generate stories that are coherent, engaging, and true to the original material's style and themes.