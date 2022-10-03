# This is the Readme File for the Anomaly Detection Repo

# Anomaly Detection
**Anomaly Detection is the practice of identifying data points, items, observations or events that do not conform to the expected pattern of a given group.**

[AnomalyDetectionCartoon.jpeg](https://ds.codeup.com/anomaly-detection/AnomalyDetectionCartoon.jpeg)

# What are Anomalies?
- **Anomaly - Anomalies are the unusual, unexpected, surprising patterns in the observed world. An anomalous data point is a deviation from a rule or from what is regarded as normal; an outlier. An anomaly is any event or measurement that is out of the ordinary regardless of whether it is exceptional or not.**
- **Outlier - An outlier is an observation that lies an abnormal distance from other values in a random sample from a population. In a sense, this definition leaves it up to the analyst (or a consensus process) to decide what will be considered abnormal. Before abnormal observations can be singled out, it is necessary to characterize normal observations. - NIST/SEMATECH e-Handbook of Statistical Methods**
- The terms "outlier" and "anomaly" are frequently used interchangeably.
- In some cases, statisticians sometimes use the term 'outlier' to mean "something I should remove from the dataset so that it doesn't skew my model I'm building".
- In other cases, we may reserve the word 'anomaly' for data points we want to keep because they are valuable if caught or costly if missed. It's also possible to have an anomaly that is an inlier, meaning that the data is anomalous in nature but is close (in distance) to the mean, mode, or expected grouping(s).

## Examples of Anomaly Detection in Data Science
- Fraud detection for financial companies
- Medical scans like XRays, ultrasounds, and MRIs seeking abnormalities in location, density, growth, etc..
- Detecting and preventing cyber-crime
- Malware detection
- Intelligence and Defense applications
- Analytical Marketing looking for new trends in business or household purchases

## The best way to detect anomalies is to know your domain
- For example, knowing that there is nothing colder than absolute zero degrees Kelvin informs how we approach an observation below 0 degrees Kelvin. It may mean that there is something wrong with the measuring tool or a clerical error like a typo (more likely).
- What determines if a data point is an outlier is a function of who determines if that data point is anomalous and why.
- One person's noise is another person's signal, depending on their goals and the costs and benefits to be gained/avoided from identifying that data point.
- To one analyst aiming for a clean model of 50/50 chance, observing a flipped coin that lands exactly on its side is an anomaly may be noise that they should ignore from their model.
- To another practitioner, the anomaly may be an observation of very high value that they want to catch, like early detection of a rare disease.
- Recall the e-Handbook of Statistical Methods definition an outlier: "an observation that lies an abnormal distance from other values in a random sample from a population. In a sense, this definition leaves it up to the analyst (or a consensus process) to decide what will be considered abnormal".