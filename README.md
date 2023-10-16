# Social Media Sentiment Analysis

Welcome to the "Social Media Sentiment Analysis with RPA" project. This UiPath automation initiative leverages the power of Robotic Process Automation (RPA) to streamline the process of sentiment analysis on social media data.

## Purpose
The proposed project is centred around the specific use case of trend identification for advertising campaigns and marketing purposes for businesses, but keeping capabilities broad for future application in other areas. The project will do this by collecting data from recent postings (or other timeframes) containing a user-provided keyword and utilising sentiment analysis to determine how the topic is perceived by the general public, providing a measurement of reception on a scale from negative to positive.

## Workflow Note
The project is written using the modern C# variant of UiPath. One of the key workflows in this project, "Sentiment Analysis," is however implemented using Visual Basic. This choice was driven by the Excel integration requirements for this project, for data transformation and analysis. Visual Basic provides the necessary capabilities to seamlessly interact with Excel data.

# Demo
Video demos are provided for both YouTube and Reddit:
 * [YouTube Demo]('YouTube Demo.mp4')
 * [Reddit Demo]('Reddit Demo.mp4')

# Usage
In order to use the workflow:

1. Open UIpath studio
2. Unzip submitted zip and open the folder UIpath studio OR Clone [this GitHub repository](https://github.com/samanthamebius/social-media-analysis) to your local machine or download it as a ZIP file.
3. Open the 'Main.xaml' file - NOTE THAT ALL OTHER FILES CANNOT BE RUN STANDALONE
4. Click the "Run" button in UiPath Studio to execute the automation process.
5. Once the program runs, you will be prompted to enter the keyword for the sentiment analysis to be performed on.
6. After you have entered the key word you will be prompted with the option to select your social media service - reddit or youtube.
7. Website of selected social media service will now begin scraping URLs and comments based on desired keyword.
8. Collected data will now show up in inputData.xlsx.
9. Sentiment analysis will now be performed by excel.
10. outputData.xlsx should now appear with aggregation of the overall sentiment from scrapped data as either: neutral, very negative, negative, positive or very positive.

**Note:** The YouTube analysis workflow works with YouTube as of 15/10/2023. Recent YouTube changes regarding ad-blocking impacts data scraping, and it has since ceased to work on some computers. Depending on YouTube A/B testing, it may not work for your computer. Reddit remains fully functional and we recommend using this.
 
## Technologies
* UiPath
* AI Centre (by UiPath)
* Microsoft Excel

## Screenshots
### Keyword Entry Dialogue
![Keyword Entry Dialogue](/image.png)

### Social Media Service Selection
![Select Social Media Service](/image-1.png)

### Sentiment Analysis Summary
![Sentiment Analysis Summary](/image-2.png)