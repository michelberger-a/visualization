# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.    
Visual 1: https://github.com/michelberger-a/visualization/blob/assignment-4/02_activities/assignments/plotly_image.png   
Visual 2: https://public.tableau.com/app/profile/alex.michelberger/viz/vaccine_coverage_map/CoverageandSummary#1
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?  
    I used python to create this image. In particular, I used the plotly package to draw this image as I wanted some interactivity.   
    The other image, I created through Tableau. I used Tableau as its free and simple to use. 

    > Who is your intended audience?  
    The intended audience would be school administrators. People who work in the Toronto school boards can use this data to ensure the student population is receiving the appropriate vaccine coverage. If there are risks to identify, such as some schools which trail below along the left y-axis, the administrators can investigate to understand why there is low vaccine coverage in those schools.  
    For the Tableau plot, a similar audience may apply, such as school administrators, but also public health workers. Users of the map may identify areas of Toronto where several schools are undercoverage, and may be worth understanding factors at play in that area. 
    
    > What information or message are you trying to convey with your visualization?  
    For this image, I am trying to convey how school size may be related to vaccine coverage. I used enrolled population along the x-axis, so as scatter points move leftward, they represent larger schools. Ideally, we would want all the data points to sit along the top of each graph, regardless of the school size. This would portray a message of ideal vaccine coverage.  
    With this visual, I am portraying a message that highlights schools across Ontario that are performing well at vaccine coverage and schools that are underperforming. This can be identified through regions of large green circles and large red circles respectively.  
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    As part of the design principles, I used colour to help identify schools which may have had low coverage rate. As a visual cue, if the data point showed a low coverage rate, colour would immediately indicate if it may be related to religion or not.  
    For the Tableau plot, a combinatiob of aesthetic features in colour and size aid the messaging. Extreme colours identify areas of high change and size does too. THe perceptual map helps with an emotional attachement, where users may identify local neighbourhoods that affect their lives. 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?  
    I ensured this visualization is reproducible by utilizing written code in python. Along wiht comments, I describe briefly each step and a web-retrieval of data. By utilizing a code based image producer, many other users can just re-run the code and create the same visual.  
    The Tableau plot is not reproducible because it was designed through Tableau. This is point and click. However, I reshaped the data through python, allowing some aspect of reproducibility to occur. With the point and click, it may be difficult to create the exact same tooltips and colour gradients, but the overall map may be easier to construct.
    
    > How did you ensure that your data visualization is accessible?  
    To ensure accessibility, I made the data interactive. There are many small points that overlap in the imaged. People with visual impairment, may be unable to distinguish different data points. With an interactive component, users can zoom in/out, and select individual data points for a tooltip on further information.   
    For the Tableau plot, I tried to ensure colour and size may help with identifying trends across the map, given RG colour blindness is common. I tried to include descriptive tooltips to explain the necessary data points if one has vision impairment. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    I think unfortunately students may be impacted by this visual. Considering some schools may have low coverage rate, administrators may want to investigate the low performance. This may unnecessarily lead to digging into student health records and asking for reasons for not vaccinating, causing a potential ethical dilemma.  
    Similar to the python plot, student may be disproprotionately affected at underperforming schools. Health or school administrators may question students as to why they are or are not getting vaccinated, which again, is an ethical dilemma related to student privacy. Local communities may be affected if local immuno-suppressed individuals are nearby and would like to understand why some people cannot protect against diseases which those immuno-suppressed indviduals are vulnerable.   
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?  
    Considering the dataset did not have many variables to select from, I only used what was necessary for the visual. Considering I wanted to look at the vaccine coverage rate, I used the the variable of the same name. I also considered variables which may have impacted coverage rate, in this case, religious exemption. Finally, I re-shaped the dataframes to create separate rows for the school year and type of vaccine.   
    I chose those variables because I wanted to create a comparative graph over two school years. I selected the two variables comparing coverage rates in subsequent years and calculated percent differences. This set up the main visual, but I also selected supporting variables like x and y coordiantes to allow the mapping mechanism to occur. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?  
    Lots of underwater labour has gone into this dataset. Administration of nurses and the health care system to record patient information and the vaccines. Toronto Public Health workers put in labour aggregating this data for the purpose of the analysis. The Toronto information management team for organizing this data in accessible formats on their website. I will add in my own labour for reshaping and creating variables for the current map. 

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
