# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 


> What software did you use to create your data visualization?
    Excel and Python (with libraries like matplotlib, seaborn and pandas).

> Who is your intended audience? 
    The visualizations illustrate the relationship between the number of registrations at library branches from 2012 to 2023 and highlight correlations between registrations and the special programs offered, such as 'KidsStop,' 'LeadingReading,' 'CLC (Computer Learning Centre),' 'DIH (Digital Innovation Hub),' 'Teen Council,' and others. The purpose of these graphs is to provide insights into what makes a library more appealing to the public, helping to identify the programs that drive the most engagement.

    The primary audiences for this data visualization include:

    - Government officials or planners who can use this data to allocate resources effectively, prioritize funding for high-impact programs, and make informed decisions about future library services.
    - Library staff and administrators who can utilize this information to better understand which programs are the most popular, optimize resources, and tailor services to meet the needs of their communities.

    
> What information or message are you trying to convey with your visualization?
     The main message is to highlight the most engaging services of public libraries, showcasing how libraries offer diverse, zero-cost events for people of all ages. The goal is to demonstrate that libraries are not just about books but are community hubs with opportunities to learn, socialize, and have fun.  
    
> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
      

    The Aesthetic principle is present in the labels and axes with appropriately sized fonts. Also, the heatmap uses color gradients to represent correlations, which makes it easier to visually spot patterns and understand the relationship between the events offered. In general, the graphs are designed to be visually appealing and to ensure the viewer can easily interpret the data. 

    The Substantive principle was used in the visualizations to accurately present the data by depicting real relationships between library registrations and the presence of special programs. The heatmap shows the correlations between various programs and registrations, and the line graph reflects the actual registration numbers over time. Both visualizations are based on real data from open data Toronto.

    The Perceptual principle is applied to make the visualizations clear and easily understood. The heatmap helps viewers understand which programs are most impactful, while the line graph offers a comparison of top-performing branches. 

    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

   To ensure reproducibility, I used both Python and Excel, which allow others to recreate the visualizations as long as they have access to the data and follow the documented steps. The files with the codes are saved in the 'assignments' folder and were named assignment_3.xlsx and assignment_3.ipynb.

> How did you ensure that your data visualization is accessible?  
    
    To enhance accessibility, I considered multiple factors while designing my visualizations:
- Used appropriately sized fonts for titles, axis labels, and annotations to ensure readability.
- Include legends and labels to help users interpret the data without confusion.
- Applied the "viridis" colormap in the heatmap, which is perceptually uniform and colorblind-friendly.
- Ensured adequate contrast between elements to make distinctions clearer, avoiding colors that may be difficult to differentiate.
 
    
> Who are the individuals and communities who might be impacted by your visualization?

     Since the visualizations try to show the relationship between registrations and activities offered by public libraries, it can be interesting to understand library utilization to allocate funding or resources effectively, with a potential to impact library planners and local community members, helping them advocate for more accessible and engaging public services.
    
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

   The features were chosen based on their relevance to answering what impacts the library registrations. So, I selected the following features:
    - Registrations: To show how popular each library is.
    - Special Programs ('KidsStop,' 'LeadingReading,' 'CLC (Computer Learning Centre),' 'DIH (Digital Innovation Hub),' 'Teen Council,' and others): To understand which types of activities attract the most engagement.
    - Branch Name: To allow for comparisons across different library locations.


> What ‘underwater labour’ contributed to your final data visualization product?

    The process involved working with two datasets from Open Data Toronto:

    - Library Branch General Information: https://open.toronto.ca/dataset/library-branch-general-information/
    - Library Card Registrations: https://open.toronto.ca/dataset/library-card-registrations/

    Data Preparation and Cleaning
    - Since the data was stored in separate files, I had to merge them using the branch codes to connect registration numbers with branch-specific attributes.
    - I focused only on physical library branches, excluding virtual branches, as my analysis aimed to understand how in-person programs impact registrations.
    - I extracted relevant columns, such as special programs (e.g., KidsStop, Leading Reading, Digital Innovation Hub, etc.) and registration numbers, to analyze their relationship.
    - Some columns contained float values that needed to be converted to integers for better readability and consistency.

    Exploratory Analysis & Experimentation
    - I initially explored other factors, such as the age of a library (PresentSiteYear), to see if it influenced registration numbers. However, the correlation was weak, so I decided to focus on special programs instead.
    - I also attempted to compare physical vs. virtual library registrations, but this didn’t align well with my main objective of analyzing in-person program impact.
    
    Choosing the Right Visualization
    To illustrate the relationship between registrations and special programs, I tested different chart types, such as, scatter plots. However, it didn’t provide clear patterns. So I chose the heatmap because they effectively display correlation strengths between multiple programs and registrations.
    
    To highlight top libraries by registration numbers over time, I experimented with stacked area charts, but the line chart was chosen for clarity in comparing trends across years.


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
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
