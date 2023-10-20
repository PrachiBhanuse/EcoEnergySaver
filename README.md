[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)

# EcoEnergySaver

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM AI service(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Project summary

### The issue we are hoping to solve

EcoEnergySaver aims to address the growing concern of carbon emissions for household electricity usage. The project's goal is to calculate and predict carbon emissions, helping individuals reduce their environmental footprint.

### How our technology solution can help

EcoEnergySaver employs IBM AI and Watson services to calculate carbon emissions for the current week and predict emissions for the next week. If current emissions are lower than predicted, users will be rewarded, and recommendations will be given for emission reduction if the current emissions exceed predictions.

### Our idea

EcoEnergySaver is a comprehensive solution that leverages IBM AI and Watson services to calculate and predict carbon emissions based on household electricity consumption. By analyzing historical data and using machine learning, our application provides users with valuable insights into their carbon footprint and empowers them to make eco-friendly choices.

More detailed information can be found in our [description document](./docs/DESCRIPTION.md).

## Technology implementation

### IBM AI service(s) used

- [IBM Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - Utilized for analyzing user feedback and comments to understand their sentiment and identify areas for improvement in reducing carbon emissions.

- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - Implemented as a chatbot to provide real-time assistance and recommendations to users on how to reduce their carbon emissions based on their household electricity usage.

- [Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery) - Used for data exploration and information retrieval to gather insights and data related to carbon emissions and energy-saving practices.

- [Watson Speech to Text](https://cloud.ibm.com/catalog/services/speech-to-text) - Employed to convert any spoken user input or voice commands into text data for further analysis and feedback.

- [Watson Text to Speech](https://cloud.ibm.com/catalog/services/text-to-speech) - Utilized to provide auditory feedback to users, such as recommendations and reward notifications, using synthesized speech.

- [List any additional IBM AI services](https://cloud.ibm.com/catalog?category=ai#services) used or remove this line.


### Other IBM technology used

In addition to the IBM AI services mentioned above, EcoEnergySaver utilizes other IBM technologies to enhance the functionality and performance of the project. These components are described below:

- **IBM Cloud Storage**: We use IBM Cloud Storage to securely store user data, electricity consumption records, and predictive models for carbon emissions.

- **IBM Cloud Functions**: IBM Cloud Functions (serverless computing) plays a crucial role in managing and automating various background processes, such as updating carbon emission predictions and sending user notifications.

- **IBM Cloud Database**: We employ IBM Cloud Databases to store user profiles, historical electricity consumption data, and reward points information.

- **IBM Cloud Monitoring and Logging**: This tool assists us in monitoring the performance and security of the EcoEnergySaver application. It also helps in troubleshooting and maintaining a smooth user experience.

- **IBM Cloud Web Hosting**: We host our web application interface on IBM Cloud Web Hosting to provide users with a responsive and accessible platform for managing their electricity usage and viewing carbon emissions data.

These components work in conjunction with IBM AI services to provide a seamless and efficient user experience. Specific details on how each component is utilized can be found in the respective sections of our codebase, which will be made available for judges to review.


### Solution architecture

Below is an overview of the architecture of the EcoEnergySaver solution:

1. **User Input**: Users input their household electricity consumption data through the EcoEnergySaver web application or mobile app.

2. **Data Collection**: The input data is collected and securely stored in IBM Cloud Storage for further analysis.

3. **IBM AI Services Integration**:
   - **IBM Natural Language Understanding**: Analyzes user feedback and comments to understand sentiment and improvement areas.
   - **Watson Assistant**: Provides real-time assistance and recommendations based on electricity usage.
   - **Watson Discovery**: Extracts insights and information related to carbon emissions and energy-saving practices.
   - **Watson Speech to Text**: Converts spoken user input into text data for analysis.
   - **Watson Text to Speech**: Provides auditory feedback, such as recommendations and reward notifications.

4. **Data Analysis and Prediction**: The collected data is processed using machine learning models to calculate the current week's carbon emissions and predict future emissions for the next week.

5. **Reward and Recommendation System**:
   - If the current week's emissions are lower than predicted, users are rewarded with incentives.
   - If emissions exceed predictions, personalized recommendations are provided to users on how to reduce their carbon footprint.

6. **User Interface**: Users access the EcoEnergySaver web or mobile interface to view their carbon emissions data, rewards, and recommendations.

The solution is designed to engage users in actively managing their electricity consumption and reducing their carbon emissions. It seamlessly integrates IBM AI services and cloud technologies to provide a user-friendly, data-driven approach to sustainability.

[Insert an architectural diagram if available to further illustrate the solution's workflow.]



### Project development roadmap

EcoEnergySaver is an evolving project with a focus on continuous improvement and expansion. While the project currently includes essential features, we have a clear roadmap for its development, aiming to enhance its functionality and impact. Our current features are as follows:

- **Energy Usage Tracking**: Users can input their electricity consumption data.
- **Carbon Emission Calculation**: We utilize IBM AI services to calculate current carbon emissions and predict future emissions.
- **Reward and Recommendation System**: Users are rewarded for lower-than-predicted emissions, and recommendations are provided for reducing emissions.

In the future, we plan to introduce the following features and improvements:

- **Enhanced Data Analytics**: We will refine our data analysis algorithms to provide more accurate predictions and recommendations.
- **Integration with Smart Meters**: Connecting with smart meters for real-time data collection to enhance user engagement and insights.
- **Community and Social Features**: Implementing social sharing and community engagement features to promote sustainable practices.
- **Carbon Offset Marketplace**: Offering users the option to offset their carbon emissions by participating in eco-friendly initiatives.
- **Mobile App Development**: Expanding EcoEnergySaver to mobile platforms for greater accessibility.

Our development roadmap underscores our commitment to continuously improve EcoEnergySaver, making it a valuable tool for users to monitor and reduce their carbon emissions while contributing to a more sustainable future.


![Uploading image.png…]()
