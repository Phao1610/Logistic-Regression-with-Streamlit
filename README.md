# Logistic-Regression-with-Streamlit
- Logistic regression 

    Logistic regression is a classification algorithm. It is used to predict a binary outcome based on a set of independent variables.

    Ok, so what does this mean? A binary outcome is one where there are only two possible scenarios—either the event happens (1) or it does not happen (0). Independent variables are those variables or factors which may influence the outcome (or dependent variable).

    So: Logistic regression is the correct type of analysis to use when you’re working with binary data. You know you’re dealing with binary data when the output or dependent variable is dichotomous or categorical in nature; in other words, if it fits into one of two categories (such as “yes” or “no”, “pass” or “fail”, and so on).

    However, the independent variables can fall into any of the following categories:

    Continuous—such as temperature in degrees Celsius or weight in grams. In technical terms, continuous data is categorized as either interval data, where the intervals between each value are equally split, or ratio data, where the intervals are equally split and there is a true or meaningful “zero”. For example, temperature in degrees Celsius would be classified as interval data; the difference between 10 and 11 degrees C is equal to the difference between 30 and 31 degrees C, but there is no true zero—a temperature of zero degrees does not mean there is “no temperature”. On the other hand, weight in grams would be classified as ratio data; it has the equal intervals and a true zero. In other words, if something weighs zero grams, it truly weighs nothing.
    Discrete, ordinal—that is, data which can be placed into some kind of order on a scale. For example, if you are asked to state how happy you are on a scale of 1-5, the points on the scale represent ordinal data. A score of 1 indicates a lower degree of happiness than a score of 5, but there is no way of determining the numerical value between each of the points on the scale. Ordinal data is the kind of data you might get from a customer satisfaction survey.
    Discrete, nominal—that is, data which fits into named groups which do not represent any kind of order or scale. For example, eye color may fit into the categories “blue”, “brown”, or “green”, but there is no hierarchy to these categories.
So, in order to determine if logistic regression is the correct type of analysis to use, ask yourself the following:

    Is the dependent variable dichotomous? In other words, does it fit into one of two set categories? Remember: The dependent variable is the outcome; the thing that you’re measuring or predicting.
    Are the independent variables either interval, ratio, or ordinal? See the examples above for a reminder of what these terms mean. Remember: The independent variables are those which may impact, or be used to predict, the outcome.
    In addition to the two criteria mentioned above, there are some further requirements that must be met in order to correctly use logistic regression. These requirements are known as “assumptions”; in other words, when conducting logistic regression, you’re assuming that these criteria have been met. Let’s take a look at those now.

- Streamlit Python

    Streamlit is an open-source (free) Python library, which provides a fast way to build interactive web apps. It is a relatively new package launched in 2019 but has been growing tremendously. It is designed and built especially for machine learning engineers or other data science professionals. Once you are done with your analysis in Python, you can quickly turn those scripts into web apps/tools to share with others.

    As long as you can code in Python, it should be straightforward for you to write Streamlit apps. Imagine the app as the canvas. We can write Python scripts from top to bottom to add all kinds of elements, including text, charts, widgets, tables, etc.

    In this tutorial, we’ll build an example app with Streamlit in Python. You’ll be able to use the common elements and commands from Streamlit and expand to others on your own!
    
- Demo

        Step 1: pip install streamlit
        Step 2: python -m streamlit run 20522028.py or streamlit run 20522028.py
        
    ![video demo Logistic Regression with Streamlit](https://user-images.githubusercontent.com/106755542/208859031-d67fc7f9-82a0-46e9-ad7b-f89c0a849493.mp4)
