
# A/B Test Plan – Hawkeye Coffee Guide

## 1. Page and Element Being Tested

The experiment will take place on the homepage (`index.html`) of the Hawkeye Coffee Guide website. The single element being tested is the main homepage headline.

- **Version A (Control):** "Find your next favorite study spot in Iowa City."
- **Version B (Variant):** "Find your next favorite coffee spot in Iowa City."

All other website content, images, formatting, and navigation will remain identical between the two versions. The only change will be replacing "study spot" with "coffee spot."

## 2. Hypothesis and Reasoning

I hypothesize that AI visitors who see Version B will report a higher likelihood of exploring the Hawkeye Coffee Guide website than visitors who see Version A.

This is because Version B communicates the website's purpose more directly by emphasizing coffee shops rather than study locations. Visitors looking for new coffee shops may find the headline more relevant and be more interested in exploring the website's recommendations.

## 3. AI Visitors, Persona, Prompt, and Assignment

All visitors will be simulated using GPT-6 with the same model and settings. Each trial will take place in a fresh conversation with no memory of previous trials.

**Persona:** A University of Iowa student who lives in Iowa City, enjoys visiting local coffee shops, and is looking for new places to study, meet friends, or grab coffee.

**Exact prompt:**

"You are a University of Iowa student living in Iowa City. You enjoy visiting local coffee shops and are looking for new places to study, meet friends, or grab coffee. Review the following website homepage as if you were deciding whether to use it. Based on the page, would you explore the website further to discover Iowa City coffee shops? Rate your outcome 0 or 1, where 0 means not likely and 1 means likely. Provide your numerical rating first with the yes or no, followed by one sentence explaining your decision."

The only difference between trials will be the homepage version provided to the AI visitor. Each visitor will be randomly assigned to Version A or Version B before the trial. A random number generator will determine the assignment, and each assignment and response will be recorded.

## 4. Primary Outcome and Measurement

The primary outcome will be the AI visitor's likelihood of exploring the website, measured using a binary, yes or no, rating scale. The numerical rating will be recorded for every trial and used to calculate the average score for each version.

## 5. Sample Size and Stopping Date

The experiment will include 100 total trials:

- 50 AI visitors assigned to Version A.
- 50 AI visitors assigned to Version B.

The experiment will stop once all 100 trials have been completed. Data collection is expected to be completed by the deadline.

## 6. Comparison and Expected Results

The average likelihood ratings for Version A and Version B will be compared to determine whether the new headline improves visitor interest. The difference in average ratings will be calculated by subtracting Version A's average from Version B's average.

A higher average rating for Version B, supported by a statistically significant difference at the 0.05 significance level, will support the hypothesis. If Version A receives a higher rating or there is no statistically significant difference, the hypothesis will not be supported.
