# Project Timeline

## 06/10/2024
- Plan for project is to make a tool that can take a listing and generate a reasonable price?
- definition is not concrete yet hence why I'll be doing more research
- ML models (regression) to take quantitative data such as number of rooms to help determine price
- Image classification / feature extraction to take images and use this to help determine price

### Current articles I am reading:
- https://www.emerald.com/insight/content/doi/10.1108/IJCHM-05-2022-0562/full/html (article1.pdf)
- - looks at using ensemble learning to predict listing prices without amenity-driven features
- https://ieeexplore.ieee.org/abstract/document/9253078 (article2.pdf)
- - 

## 10/10/2024
### Plan for next meeting
- Discuss ethics issues (asking other people to test our tool or if we'll need other people's data to train models)
- Structure of tool
- Work on smaller city such as Bristol
**Define Key Problems:**
Pricing Recommendation:
- Use regression models to predict optimal pricing based on factors such as location, size, amenities, and seasonality.

Occupancy Prediction:
- Use classification or regression to predict occupancy rates based on time of year, price, and property features.

Feature Importance:
- Use feature importance techniques (e.g., in Random Forest, SHAP values) to determine which property features correlate with higher prices or bookings.

Ask about model training (using Colab and getting paid plan)

Overall goal is to create a tool to predict pricing, occupancy and feature importance for Airbnb hosts.


## 23/10/2024
Work on literature review and cancel meeting this week. Work has not been sufficient enough to warrant a meeting

## 31/10/2024
- So far, have written about a page
- Need to work on it until Sunday and produce a good few more pages by then for the next meeting.

## PLAN (written roughly 11/11/2024):
- Continue introduction by explaining smart pricing and its competitors, talk about maximising revenue while keeping occupancy rates high
- For context, talk more about airbnb, pricing landscape, (with regular properties too), factors influencing price (location, seasonality, demand)
- Highlight how price impacts hosts and guests and relevance to the broader industry
- Talk about market segmentation (who stays at airbnbs, what drives their preferences, customer types, factors that influence decisions, domain knowledge)
- Data availability (data techniques, compare inside airbnb vs scraper), delve into legal and ethical aspects
- Key literature review comparing papers, what techniques they're using, highlighting best techniques, compare strengths vs limitations, focus on pieces directly related to airbnb pricing.
- foundational materials such as books.
- Specifications (functional vs non-functional requirements)
- Risk assessment
- Evaluation
- Conclusion

# PLAN FOR TODAY
- Put bulk of intro into context
- Gantt chart for timeline
- Use figures and talk about low-end pricing and high-end pricing. Reference airbnb search queries
- Follow spec and write accordingly. Objectives could be done in paragraphs outlining priority etc.

- hypothesis statement being that customers will get a better experience with renting out properties and earning profit
when using my pricing tool 

- talk about ML techniques that are relevant (like random forests, standard LR, not MLR etc)


# RECENT MEETING NOTES (22/11/2024)

- Straight away say what I want to do  
- “The following sets out background info on Airbnb and who uses it”  
- Not sure if they have a good choice if they don’t have a bigger idea  
- Remove first big sentence up to market pricing in market segmentation. It’s a filler sentence  

- Market segmentation is different types of customers (tourists, commuters etc)  

- First part of page 3 is relevant  
- Remove all irrelevant references in market segmentation (keep (6))  
- Remove irrelevant stuff. Don’t talk about water acces theme parks etc  

- When talking about smart pricing, be wary of trademark  

- Use own Google trends plot  
- Download csv file and make own plot  
- Draw lines at peaks and compare seasonality  

- Introduce paper, within paragraph, don’t make any more references  
- Key lit review section has too many references on 13  

- Don’t write too much on one paper  
- Remove last two figures since they don’t add much  

## Two things to talk about:
- Problem of setting initial price  
- Dynamic pricing which is more complex  

- Separate and look at papers on how to price airbnbs in a basic way  
- Others trying to capture dynamic info  
- Look at papers talking about pricing in a boring sense  
- Don’t have to do Gantt chart. Can just detail tasks in order  
- Can say the outcome and milestone for each task  

- Compare dynamic pricing algorithm to airbnbs  

### Tasks:
- Task 1: collect data (1st-14th dec)  
- Task 2: explore data  
- Looking at reproducing the work from 13  
- Task 3: feature selection  
- Task 4: model building  

- If one of outcomes is to reproduce the tool from paper / Airbnb  

- How to take market information and dynamically suggest a price based on  
- Talk about what models the papers used  

- Project plan has to align with papers analysed  
- How will I evaluate output  
- What will I add to the papers  
- Can’t say I’m doing dynamic pricing if I don’t know where I’ll get data from  

## Break into Two Phases:
1. Static analysis  
   - Scraped Airbnb data  
   - What is price next Wednesday to hire house  
   - (number of rooms, location, facilities)  
   - (don’t look at seasonality / events / demand)  
   - (requires different info and testing)  

2. Own dataset looking at future prices of properties based on accessing info with API then implement dynamic pricing for a person  

- Show ambition in plan. Seem slightly difficult  
- Test pricing algorithm to default what people apply vs what Airbnb does vs what is suitable  
- Decide on evaluation strategy in project plan  

- Trying to estimate demand curve based on dataset (figure 6 in paper 13)  

- Write about paper 13 saying how Airbnb tried recreating the model. Make sure to mention Airbnb  
- Say what they have access to and what I don’t have access to  
- Potentially can determine  
- Compare myself to their dynamic pricing algorithm  
- Create database of properties using dynamic pricing and compare how mine compares to theirs.  
- Can tell if they’re using dynamic pricing by pricing goes up and down  
- Look at dynamic pricing in a field like hotels to have an idea of a general sense  
- If can’t find more on dp on Airbnb, look at the hotels ones  
