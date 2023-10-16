Social Media Sentiment Analysis

Welcome to the "Social Media Sentiment Analysis with RPA" project. This UiPath automation initiative leverages the power of Robotic Process Automation (RPA) to streamline the process of sentiment analysis on social media data.

Purpose
The proposed project is centred around the specific use case of trend identification for advertising campaigns and marketing purposes for businesses, but keeping capabilities broad for future application in other areas. The project will do this by collecting data from recent postings (or other timeframes) containing a user-provided keyword and utilising sentiment analysis to determine how the topic is perceived by the general public, providing a measurement of reception on a scale from negative to positive.

Workflow Note
The project is written using the modern C# variant of UiPath. One of the key workflows in this project, "Sentiment Analysis," is however implemented using Visual Basic. This choice was driven by the Excel integration requirements for this project, for data transformation and analysis. Visual Basic provides the necessary capabilities to seamlessly interact with Excel data.

Usage
In order to use the workflow:

1. Open UIpath studio
2. Unzip submitted zip and open the folder UIpath studio OR Clone [this GitHub repository](https://github.com/samanthamebius/social-media-analysis) to your local machine or download it as a ZIP file.
3. Click the "Run" button in UiPath Studio to execute the automation process.
4. Once the program runs, you will be prompted to enter the keyword for the sentiment analysis to be performed on.
5. After you have entered the key word you will be prompted with the option to select your social media service - reddit or youtube.
6. Website of selected social media service will now begin scraping URLs and comments based on desired keyword.
7. Collected data will now show up in inputData.xlsx.
8. Sentiment analysis will now be performed by excel.
9. outputData.xlsx should now appear with aggregation of the overall sentiment from scrapped data as either: neutral, very negative, negative, positive or very positive.

**Note:** The reddit web scraping process can take some time. Please allow 20-30s for the page to be scraped. For this reason, it is limited to the comments of 2 reddit posts for time reasons. This can be adjusted.
 
Technologies
* UiPath
* AI Centre (by UiPath)
* Microsoft Excel
