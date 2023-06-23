# Project Copyright

This project utilizes various technologies and libraries to provide powerful functionalities. Below is an overview of how each component was used:

## Technologies Used:

- **YouTube API**: Integrated the YouTube API to retrieve channel information, video data, and comments from YouTube. This involved authenticating the API requests and handling the API responses.

- **Streamlit**: Utilized Streamlit, a web application framework, to create an interactive dashboard for the sentiment analysis tool. Developed user interface components, such as text inputs, buttons, and data visualizations, to enhance user experience.

- **Flask**: Implemented a backend API using Flask, a micro web framework, to handle data processing tasks. The API received requests from the frontend, processed the data using TextBlob for sentiment analysis, and returned the results to the frontend.

- **Docker**: Employed Docker for containerization, enabling easy deployment and scalability of the application. Created Docker images for the frontend, backend, and data processing components, allowing them to run independently and communicate with each other through defined interfaces.

- **TextBlob**: Utilized the TextBlob library, a powerful NLP tool in Python, for sentiment analysis of the extracted comments. Performed sentiment classification on the comments to determine their polarity (positive, negative, or neutral) and subjectivity.

## Functionalities:

The project offers the following functionalities:

- Retrieve channel information and latest videos from YouTube using the YouTube API. Display relevant details such as video titles, views, and publish dates.

- Extract comments from the videos and perform sentiment analysis using TextBlob. Process the comments to determine their sentiment scores and categorize them into positive, negative, or neutral sentiments.

- Generate visualizations, such as word clouds and sentiment charts, to analyze the sentiment of the comments. Present the sentiment distribution visually to provide insights into the audience's reactions.

- Display a data frame with the extracted comments for further analysis. Present the comments in a tabular format, allowing users to explore the raw data and perform additional manipulations or computations.

This project demonstrates the integration of different technologies and libraries to create a comprehensive sentiment analysis tool for YouTube channels. The combination of YouTube API, Streamlit, Flask, Docker, and TextBlob enables seamless data retrieval, processing, and visualization, empowering users to gain valuable insights from YouTube comments.
