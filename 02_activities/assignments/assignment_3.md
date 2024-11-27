# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Map of Koreans: https://www.reddit.com/r/dataisugly/comments/1gwgk42/nationality_of_foreign_residents_in_south_korea/  

        I do no think the image is accessible because one of the major accessibility issues in the visual is the use of colour.   
        In the smaller pie graphs, the colour gradients may not have a strong enough contrast for someone with vision impairment.   
        For example, the light blues to blue and the light reds to red would be difficult to tell apart.   
        Same can be said for those smaller blue dots in the oceans.   
        For the text, although the visual uses sans-serif typeface, the font is small, likely less than size 12, making it difficult to read for viewers with vision impairment.   
        One strength of this image, is it can be accessed in a number of browsers, but also has a zoom function which does not distort the image.   
        This allows users to actively increase the viewing area of the image.   

        Graph of Internet Browsers: https://datavizproject.com/wp-content/uploads/examples/Sk%C3%A6rmbillede-2016-01-23-kl.-17.36.42.png  

        I do no think the image is accessible as one of the major accessibility issues in the visual again, is the colour. Some of these colours may blend together for readers that have RG-colour blindness.  
        Another issue is the accessibility of opening the image. On the site, there were many issues in finding a link that worked. Saving the image to a new page and taking the link from where was the only method that worked and may be difficult for users to access.  
        The numbers in each box are white and contrast the boxes quite well, allowing for an easier reading experience. The typeface is also sans-serif, and there is a legend to support the image, mapping colours to the appropriate browser. However, the font could be slightly larger.  
        The image does follow Government of Canada Standards, by utilizing the same formatting for headers (title and legend) so that screen readers can pick them up appropriately. It appears they used header style functions instead of changing the boldness, or font. 

        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Map of Koreans:  
        For this map I would institute a couple changes.  
        First, I think changing the blue water to a pure white instead would allow for greater contrast between the written text and colours in the pie graphs.  
        I think if the map were split up into subregions (i.e. continents), there could be a reduction in the amount of information piled into one page.  
        In response, the text could be larger with better spacing for readable font.  
        By focusing on different continents, alt-text can be included to provide a brief description of the image, help those with vision impairment understand the image. Following GOC standards, the alt-text should be plain language, left aligned, and maintain consistent formatting to reduce confusion.  
        The alt-text should describe the main visual, and a key difference from the other continent maps, such as countries with the highest number of male/female Koreans (level 2). 

        Graph of Internet Browsers:  
        As for the colours, I would implement a better palette not subject to colour blindness impairments, such as the viridis palette. Considering there are only 5 different browsers in the graph, the viridis palette should suffice.  
        I would want the contrast between teh adjacent blocks to be greater, so the different browers are more readable.    
        On the issue of accessible, I would want the image to be accessible in the browser where you can zoom in. The format of the image would need to change and likely need to be accessible through other mediums (similar to the Korean graph).  
        I would also like to add an alt-text to this graph. For this image, I would use the alt-text to describe the main x and y axes, the different browsers being compared and the purpose of the graph.  
        I would also include some highlights of key statistics, such as the browser with the greatest proportional share in 2009 and in 2013, reprsenting level 2. 



        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:
| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
