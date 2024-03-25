### • How did you get the data (legally....)?  
We managed to acquire the data on troops through the GitHub repository (mentioned in the video + datasheet). The data about our defenses was obtained from scraping the Clash of Clans wiki fandom website.

### • Did you check the source?   
Data was mostly obtained from the official source and the rest of the data could easily be checked against the source of truth (Clash of Clans wiki). It is also fairly easy to check if the data retrieved was the same as the one present in the game (accessible through any mobile phone).

### • Are there considerations about the analysis you made?  
The analysis is only relevant for players before or at exactly town hall level 9. More advanced players at town hall level 10+ have access to more resources which were not covered in our analysis.

### • Did you have to make decisions that affect the analysis?  
We’ve had to rule out the healer which is an outlier since it does not deal any damage. Spells were ignored as they were in their own category, not having stats comparable to other troops. Hero powers were also ruled out: it is fairly difficult to quantify “healing” or “rage” effects within our analysis. Solutions were explored, but none of them proved to completely remove any bias in our analysis, so these were simply excluded.


### • What are the limitations of your analysis and your conclusions?  
The limitation of our project is that we only take unit strength into account and not team composition, this can be a perfect future work part to see which troop combinations are the most optimal, same for the defenses we only looked at single performance and not combined or placements of the defenses.

### • Who are the stakeholders of your project?  
We don’t have any stakeholders in our project that helped us directly in the project outcome, nonetheless, the GitHub page and the fan wiki helped us gather the information needed to arrive at our conclusions.  

### • Who can benefit from this project, who can be harmed, who is excluded, etc.  Maastricht University  
Any clash of clan players getting close or who is already town hall level 9 can benefit from this analysis. It might not be relevant for very competitive and advanced players who are further apart from town hall level 9 and have access to new troops and heroes not discussed in the analysis. 
