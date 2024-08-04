# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

- Selected Dataset: 
  - Child Care Centres in the City of Toronto 
  https://open.toronto.ca/dataset/licensed-child-care-centres/

- For each visualization, describe and justify: 

    Viz-1 
    > What software did you use to create your data visualization?
    Python & Tableau 

    > Who is your intended audience? 
    Government Department who want to understand the child care centers and their subsidy. 
    
    > What information or message are you trying to convey with your visualization? 
    - There is a bigger difference in different Operating Auspice in terms of their capacity to operate. 
    - Public(city operated) child care centers are having smaller capacity as compared to non-profit and commercial agencies. 


    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    - I preferred substative component more then others. My preference was to get some inights from the data that is relevant and accurate. 
    - I also considered aesthetic and percentual components through clear labels and legends, use of colors, clean layout and consistent style. 
  

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    - Python: 
      - Saved the dataset in the folder for reproduction 
      - All the import libraries are added in the code 
      - Code can be re-run to generate same visuals. 
    - Tableau: 
      - Data Extract had been uploaded to the tableau public profile
      - Tableau dashboard can be refreshed to generate same visualizations. 


    > How did you ensure that your data visualization is accessible?  
    - Python: 
      - Color contrast was selected to ensure accessibility 
      - legends are added 
      - axis and title fonts and color scheme are supportive 
    - Tableau: 
      - Same as above 

    > Who are the individuals and communities who might be impacted by your visualization?  
    - All the residents of Toronto who are parents 
    - Child care owners and staff 
    - Ontario Government 
  

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    - Feature engineering was performed 
    - Exploratoty data analysis was done to identify any relationships 
    - Multiple visualizations were created to see if there is any interesting relationship. 

    > What ‘underwater labour’ contributed to your final data visualization product?
    - Binning was needed in tableau for histogram 
    - Initially I tried to read geojson file directly in tableau but I couldn't succeed. Same was the case in python. 
  

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
